# A list of all of ripmes config options and what they do
### To change these option on your ripme install edit the rip.properties file

file.overwrite     | bool | If true ripme will overwrite existing files rather than skip them

clipboard.autorip  | bool | If true ripme will try to download any links in the clip board

error.skip404      | bool | Don't retry on 404 errors

download.save_order| bool | If true ripme will prefix each downloaded file with a number in the order the file was download

auto.update        | bool | If true ripme will auto-update every time it's started

tumblr.get_raw_image | bool | If true the tumblr ripper will download the image in the size it was uploaded in

play.sound         | bool | If true ripme will play a sound every time a rip finishes

download.show_popup| bool | TODO figure out what this is for

log.save           | bool | If true ripme will save it's logs

urls_only.save     | bool | If true ripme will save all urls to a text file and download no files

album_titles.save  | bool | Currently does nothing

prefer.mp4         | bool | Prefer mp4 when downloading a video that has more than 1 format

history.warn_before_delete | bool | If true ripme will prompt the user with a "Are you sure?" box when clearing ripmes download history

instagram.download_images_only | bool | If true the instagram ripper will skip videos and only download images

download.timeout   | int  | File download timeout (in milliseconds)

page.timeout       | int  | Page download timeout (in milliseconds)

download.max_size  | int  | Maximum size of downloaded files in bytes

threads.size       | int  | The number of threads to use

twitter.max_requests | int | TODO figure out what this is for

twitter.auth       | String | Twitter API key (Base64'd)

tumblr.auth        | String | Tumblr API key

log.level          | String | The debug log level (Example: Log level: Debug)

gw.api             | String | TODO figure out what this is for


