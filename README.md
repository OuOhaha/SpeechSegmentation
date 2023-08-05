# SpeechSegmentation
 Automatically split audio with the assistance of whisper.<br><br>
 Mainly support cutting audio files in "mp3" and "wav" formats, using the "tsv" format output from whisper as timestamps. The audio files and tsv need to have the same name. If you want to modify the filename, make changes in "settings.txt".<br><br>
 *The first line should represents the file name, and the second line represents the file extension, otherwise the errors may occur.*<br><br>
 Execute "cut.py" to perform audio file segmentation.<br><br>
 Example(execution)<br><img width="478" alt="Sample" src="https://github.com/OuOhaha/SpeechSegmentation/assets/85870447/d871551a-f3d8-4cc8-9026-d7eb34d63674"><br>

 If you haven't set up the Whisper environment yet, click here -> [openai whisper](https://github.com/openai/whisper "openai whisper")
