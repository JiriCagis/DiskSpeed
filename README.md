<h1> Disk Speed </h1>
It is terminal utility for detections your average disk speed with write date to disk. 
Utility is simple for use, only put this file on disk when you want measure disk speed and you write to console:
<pre>
python disk_speed.py
</pre>
Without parameter utility works with default values, write 1MB block 50x to disk and it calculates speed. You can parameterized too, it use following form:
<pre>
python disk_speed [size block] [unit | K,M,G] [count block]
</pre>
