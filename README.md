# audioanalyzertotxt
import an audio track and it will analyze it into a .txt file. works as a spectrum analyzer

i personally use it for scratch projects lol. [this one](https://scratch.mit.edu/projects/871290212/)

## link to the tool:
## https://smashhits.github.io/audioanalyzertotxt/

### notes
also sorry that it doesnt render fast even though this is a small project, you have to listen to the entire audio file before downloading.
i might fix this later, i just dont feel like doing it right now

there may be problems with this that i am too blind to spot, so tell me if you have any problems or recommendations

## How to read the exported txt file?
the txt file is pure frequncy data, which means there arent any time markings, tempo data, or anything like that.
there are 64 values per frame (32 for left, and 32 for right) at 30 frames per second
with the highest number on the list being the lowest frequency of the 32 values
here is an example of 1 frame worth of values:

241 --- all this is the left channel for 1 frame
237
216
194
184
178
171
165
162
156
154
150
147
146
142
138
137
135
136
131
131
131
129
125
121
106
64
0
0
0     --- it gets empty near the end because sounds usually are at the enjoyable hearing range for humans
0
0
0     --- this is the end of the left channel for this frame
0     --- this is the start of the right channel for this frame
0         it is empty becuase the sound file i used had sound only in the left channel
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0
0     --- this is the end of the right channel for this frame
