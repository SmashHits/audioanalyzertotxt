# audioanalyzertotxt
import an audio track and it will analyze it into a .txt file. works as a spectrum analyzer

i personally use it for scratch projects lol. [this one](https://scratch.mit.edu/projects/871290212/)

## link to the tool:
## https://smashhits.github.io/audioanalyzertotxt/

## what is v1/v2.txt and how do i open it?
they are just old versions of the code, you open it by downloading the file and renaming it to example.html it will then run in your browser

### notes
sorry that it doesnt render fast even though this is a small project, you have to listen to the entire audio file before downloading.
i might fix this later, i just dont feel like doing it right now

there may be problems with this that i am too blind to spot, so tell me if you have any problems or recommendations

## How to read the exported txt file?
the txt file is pure frequncy data, which means there arent any time markings, tempo data, or anything like that.
there are 64 values per frame (32 for left, and 32 for right) at 30 frames per second
with the highest number on the list being the lowest frequency of the 32 values

to see an example of this, go to example.txt
