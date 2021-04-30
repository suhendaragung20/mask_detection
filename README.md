# mask_detection

how to use: 

python app_v2.py -s source -v level

source | deskripsi
--- | --- 
0 | untuk input external kamera index ke 0
1 | untuk input external kamera index ke 1
rtsp://admin:QPPZFE@192.168.100.98:554/H.264_stream | url rtsp


level | deskripsi
--- | --- 
1 | default 1x1 fragment inference
2 | 2x2 fragment inference (lebih lambat 4x, namun bisa mendeteksi objek yg lebih kecil)


output stream dapat di akses di laman
localhost:5003/
