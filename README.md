# DockerNotes


 إزاي تشوف محتوى Volume في Docker؟
لو عندك volume اسمه myvol، وتحب تشوف إيه جواه:

1. شغّل Temporary Container يفتحلك عليه:

2. 
docker run --rm -it -v myvol:/data busybox sh


ثم داخل الـ container ده:




cd /data


ls -l


دا هيعرض كل الملفات اللي موجودة داخل الـ volume.
