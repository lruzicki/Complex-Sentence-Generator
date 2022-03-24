# Complex-Sentence-Generator
Program using n-grams to generate complex sentence from given seed. Dictionary is based on 9 books provided by NLTK.

Used:
- Python
- Natural Language Toolkit

How does it work:
- program gets seed
- imports texts to generates bigrams and trigrams, then sort them by frequency 
- one of the 10 n-grams is choosen, then last word is a new seed
- check if length, ending words are correct and then generate new sentence and if the word is not found in dictionary it looks for synonyms and use them as a seed


Example:

seed: "Man"
words: 503

Output:
”Man Who are these other things have been a dream or of the Marquis was a
man. Who may well be in time the red hair and rather. Remarkable noble face
is true early Christians were I say. That there was something bulky and then
the Colonel Ducroix. Smiled brightly enough as the Christians in this respect
to the world he would have. I can behave like those of Saffron Park I father
expand into the landscape was. Only tell you the Professor worn I am not to
tell. Nobody eats him and his hand across his seat shuddering as such truth.
Can see something more or less I can be I tell you are not think that there is
only. One glance over his forehead was lifted. The Colonel suggested that it
is an artist had fallen upon it was. That he did not a man with one of those
emptied hell only for. Me in the dark from the President or the man I tell you
are a sort of which he. Cried the Marquis ate casually and conventionally of
the President in a man. Of it was a kind of which he could not really. A little
man with his large but indecipherable face of the end of him. I can be I am
going suddenly stone I say that he is it seemed to have. A moment staggered
the Professor was staring. I am a portrait of the Professor de Worms swung.
I am going to know what you I can. I am not a pair of the world would. Be
with a curious freedom and I I father cultivated I can see something more than
the Marquis sprang back of the other. Sense as he spoke in a little vague. I
am not a kind of him to the. Professor worn them as a voice that I I tell you
father playing fell again into the. Secretary has a motor round and they could
have sworn that he said in. I can be I am afraid we have not been wavering
across the square beneath. Him like a man was a little. Vague hands rose like
a woman has ever be quite suddenly took. Off a matter of his own safety. I am
now going suddenly stone passage so that by this time to catch it is not think.
That he said in a moment Gregory sprang back. Quite simple that is not a kind
I tell you are a pair of it must. Be a matter of all the Marquis de I say that
they were still. Fixed and they could almost fancy that he had been wavering
across the. End of Saffron Park lay on the river and the end I say. That we are
all Syme looked straight into his head out of the Marquis. Casually and at the
world is full of shattered sunlight. And sat down once or twice two got into the
room with a kind. Of all sorts of it seemed to be a kind of Saffron Park..”
