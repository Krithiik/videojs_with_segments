# videojs_with_segments

I was'nt able to record the screen so i used my mobile.

The working video is here - https://drive.google.com/file/d/1DcCqFsLoPOtofwIF9rpKP7ldceOJtIaP/view?usp=sharing

Used videojs documentation to understand certain built in functions and used them appropriately.</br>
Used videojs-marker plugin for markers over the player.

Improvements that can be made:

=> Timestamp is in HH:MM:SS format and there are times when we need to get the total seconds instead of a timestamp. So, we can include a data column in seconds for each segement start timestamp and reduce the computations

=> We can reduce some un-neccesary renders using SPA frameworks, since the timestamp changes but the segment name doesnt change over the segment period.

=> I used a "data.json" file which i read mulitple times, instead if we use a DB the data read can be only once.
