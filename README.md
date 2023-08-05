# SpeechSegmentation
 Automatically split audio with the assistance of whisper.
 Mainly support cutting audio files in "mp3" and "wav" formats, using the "tsv" format output from whisper as timestamps. The audio files and tsv need to have the same name. If you want to modify the filename, please make changes in "settings.txt".<br>
 *The first line should represents the file name, and the second line represents the file extension.; otherwise, errors may occur.*<br>
 Execute "cut.py" to perform audio file segmentation.<br>
 
 If you don't have whisper environment yet, check this -> [openai whisper](https://github.com/openai/whisper "openai whisper")
