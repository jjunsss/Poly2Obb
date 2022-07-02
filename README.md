# Poly2Obb
Polygon(segmentation) annotation to Oriented Bounding Box data annotation.  
Result is OBB box points. [[x1, y1], [x2, y2], [x3, y3], [x4, y4]]


#1.Original Image

<img src = "https://postfiles.pstatic.net/MjAyMjA1MjdfMTQ3/MDAxNjUzNjE0NjA5MjMw.YInVTv168jQbGIy5oE4DpRZJVcTi806DsM8T108rbZAg.AoSHWTYNkfsezOESjEdTUDFv2q6vaUA0fAov59dlyQwg.PNG.jjunsss/image.png?type=w773" width = "200" height = "200" alt = "original image">

---
#2. Polygon line Drawing

<img src = "https://postfiles.pstatic.net/MjAyMjA1MjdfNDUg/MDAxNjUzNjE0NzE3NjQy.DKaF5bVfLqaKVMcXK7WrrjRMEYCsW3Qv3pdNJm3deXIg.c-IlBXRIbpCnwn8k6i7BSvWK4bn59EiB3fucphSkRZAg.PNG.jjunsss/image.png?type=w773" width = "200" height = "200" alt  = "polygon img">

---
#3. Polygon line with OBB

<img src = "https://postfiles.pstatic.net/MjAyMjA1MjdfMjk0/MDAxNjUzNjE1Mjk0Mjk3.D35rvkrOTnsk3J6EN5WZSP6qk3YqUV_UeoGg87724LYg.snJN6_xucu7mnncnVJsyX-KHQT7s6eP79o1KEtO5rd4g.PNG.jjunsss/SE-7440904a-7ee0-4467-8477-d5136347a753.png?type=w773" width = "200" height = "200" alt  = "polygon img">

---
#4. 4 state img

<img src = "https://postfiles.pstatic.net/MjAyMjA1MjdfNzgg/MDAxNjUzNjE1NDg3MDE4.6RbOM00D8fHEezwpWr-SF3kXKsrKRWaXaCofESN2Dcwg.Suw7QFzhfcCIaFlMeqZQ8VQV2f00DtUGaLeOxCrKneEg.PNG.jjunsss/image.png?type=w773" width = "300" height = "300" alt  = "4 state img">

Clock-wise
1. roboflow-obb points
2. original polygon img
3. roboflow-obb points ( edge polygon state )
4. my polygon2OBB result

( 3th img is just to identify the OBB conversion in edge condition of POLYGON annotation. )
( 4th img is the result of my poly2obb conversion )
