# Poly2Obb
Polygon(segmentation) annotation to Oriented Bounding Box data annotation
result is OBB box points.


#1.Original Image

<img src = "https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d516b0c3-dff5-45d7-a378-26801cab8492/Untitled.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45/20220517/us-west-2/s3/aws4_request&X-Amz-Date=20220517T064933Z&X-Amz-Expires=86400&X-Amz-Signature=6b8d44a891fb69685259a5aa67e3bf20009bbd1a062f0cda4ca6efc3aae768ef&X-Amz-SignedHeaders=host&response-content-disposition=filename%20=%22Untitled.jpeg%22&x-id=GetObject" width = "200" height = "200" alt = "original image">

---
#2. Polygon line Drawing

<img src = "https://s3.us-west-2.amazonaws.com/secure.notion-static.com/380390de-ed1f-444a-a75a-7bbbe4cbcab9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220517%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220517T065751Z&X-Amz-Expires=86400&X-Amz-Signature=046cc38077159fa5d88cfa9efe483a7742e705dab4cd820d754f613892e7cb4b&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width = "200" height = "200" alt  = "polygon img">

---
#3. Polygon line with OBB

<img src = "https://s3.us-west-2.amazonaws.com/secure.notion-static.com/bb692708-eebb-44cd-a9f6-fbffcd243bf2/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220517%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220517T070241Z&X-Amz-Expires=86400&X-Amz-Signature=8b9ca08f19a80bddeab92d1c3dd4ba8fef64819de5cd4dff51e9ecdc9735bf16&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width = "200" height = "200" alt  = "polygon img">

---
#4. 4 state img

<img src = "https://s3.us-west-2.amazonaws.com/secure.notion-static.com/b080e1d7-6793-492b-8ddd-c0f589b2485c/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220517%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220517T070435Z&X-Amz-Expires=86400&X-Amz-Signature=0a25d663af899f1847913ed53e35c1ef93b0b38bf52c096ea03f42001b01b5a5&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width = "300" height = "300" alt  = "4 state img">

Clock-wise
1. roboflow-obb points
2. original polygon img
3. roboflow-obb points ( edge polygon state )
4. my polygon2OBB result

( 3th img is just to identify the OBB conversion in edge condition of POLYGON annotation. )
