Old (West) Norse, Reconstructed
===============================

This project aims to collect many resources, particularly useful for those whom
are teaching themselves or others the language of Old Norse as spoken over a 
thousand years ago. If you are an actor playing a viking in a movie, or if you 
are re-enacting a viking event, then this material should be useful to you.

I searched for a project like this, but I didn't find any that were exactly
this sort of project, with any centralized organization or hub, that
facilitates collaboration the way github does. So I decided just to create one.

This project is using Classical/Reconstructed Pronounciation as opposed to the
modern Icelandic one. The aim of this project is to make it as easy as possible
for people to emerse themselves in Old Norse and rapidly aquire fluidy in both
the spoken and written language. Additionally, we aim to create standardized
tags for grammar and pronounciation rules which will be useful for software
which accepts Old Norse sentences as input, and performs analysis, to identify
examples of rules which are illustrated and point out that illustration to
students.

Currently, I have taken some sounds from a youtube video to provide examples.
Another potentially fun source for audio from the History Channel's Vikings
series, which if I recall, has some scenes with reconstructed Old Norse in
them.  It would be very nice if we can extract those scenes and also provide
subtitles in the standard orthography, to help newcomers shift their Brain's to
'Old Norse'-mode.

In my experience with some parts of language acquisition, I have found it can
be helpful to have a live chatroom. To that effect, I invite you to join me
in  #OldNorseHub on the Freenode [IRC](http://xchat.org/) Network.

Since, I want, to some extent, to revive the language, I propose perhaps
marking newly coined terms with an unused symbol, so that we can use them with
eachother and still recognize that they are not authentic Old Norse. Perhaps we
can steal vocabulary from modern Icelandic, and mark such 'stolen' words.  For
example, appending 'I' to the end of back ported modern Icelandic terms.


Helpful Resources:
 * [Youtube Video for Reconstructed Pronounciation](http://www.youtube.com/watch?v=JICgNRzENoQ)
 * [Old Norse Grammar - on a single page!](http://oldnorsenews.org/2008/08/old-norse-grammar-on-a-single-page/)
 * [Old Norse I: Grammar - Viking Society Web Publications](http://www.vsnrweb-publications.org.uk/NION-1.pdf)
 * [Yahoo Group, Study Group, Class](https://groups.yahoo.com/neo/groups/norse_course/info)


Old Norse Vowels (Reconstructed)
===============================

RULE: p_vLong - vowels marked with the accent mark are elongated versions of the unmarked vowels  

        Note:

        XSS (X-sampa-sim) is a contrivance. It is useful for situations where it is
        convenient to use the  IBus x-sampa-ipa input method, even though you are
        typing letters from the Old  Norse Alphabet as opposed to IPA characters.

	Note:

        All runes in this document should be taken with a grain of salt. There is no
        standard runic orthography as far as I am aware. I wanted a runic orthography
        that is as complete as possible, so it is here actually a mix of elder futhark,
        younger futhark and danish futhark.

Vowel | [IPA][1]  | Description                | Example word                            | X-Sampa | XSS | [Vim][vim] Digraph 
----- | ---- | ------------------------------- | --------------------------------------- | --- | ------- | ------------------
á     | [aː] |  as in english father           | ár ‘year’, [:sound:ást][ást] 'love'     |  a: |  _Ha    | a'        
a ᚨᛅᚪ | [a]  |  the same sound, but short      | dagr ‘day’, [þat][þat] 'it,that'        |  a  | a       |           
      |      |                                 |                                         |     |         |           
é     | [eː] |  as in french été, but longer   | él ‘storm’, [tré][tré] 'tree'           |  e: | _He     | e'        
e ᛖ   | [e]  |  as in french été               | ben ‘wound’, [ek][ek] 'I'               |  e  | e       |           
      |      |                                 |                                         |     |         |           
í     | [iː] |  as in english eat              | lítr ‘looks [vb.]’,[ís][ís] 'ice'       |  i: | _Hi     | i'        
i ᛁ   | [i]  |  the same sound, but short      | litr ‘colour’,[minn][minn]              |  i  | i       |           
      |      |                                 |                                         |     |         |           
ó     | [oː] |  as in french eau, but longer   | sól ‘sun’, [dró][dró]'drew'             |  o: | _Ho     | o'        
o ᛟᚬᚩ | [o]  |  as in french eau               | hof /hov/ ‘temple’ [sofa][sofa] 'sleep' |  o  | o       |           
      |      |                                 |                                         |     |         |           
ú     | [uː] |  as in french bouche, but longer| hús ‘house’                             |  u: | _Hu     | u'        
u ᚢ   | [u]  |  as in french bouche            | sumar ‘summer’, [kunna][k1] 'know'      |  u  | u       |           
      |      |                                 |                                         |     |         |           
ý     | [yː] |  as in french rue, but longer   | kýr ‘cow’, [spýta][spýta] 'spit'        |  y: | _Hy     | y'        
y ᛦᚣᚤ | [y]  |  as in french rue (en:few)      | yfir ‘over’, [kyn][kyn] 'family/kin'    |  y  | y       |           
      |      |                                 |                                         |     |         |           
æ ᛟᚫ  | [æː] |  as in English pat, but longer  | sær ‘sea’, [mæla][mæla], [nær][nær]     |  {: | {       | ae        
      | [ɛː] |  as in English bed, but longer  | alternatively: [/mɛːla/][m], [/nɛːr/][n]|  E: | {       |           
      |      |                                 |                                         |     |         |           
œ ᛟ   | [øː] |  as in French feu, but longer   | œrr 'mad’,  [grœn][grœn] 'green'        |  2: | 9       | oe        
ø ᛟ   | [ø]  |  as in French feu (en:bird)     | døkkr ‘dark’, [øx][øx] 'axe'            |  2  | 9       | o/        
      |      |                                 |                                         |     |         |           
ǫ ᛟᚭ  | [ɔ]  |  as in English hot,thought      |  [ǫl][ǫl] ‘ale’, [hǫll][hǫll] ‘hall’    |  O  | _co     | o;        


[1]: http://en.wikipedia.org/wiki/International_Phonetic_Alphabet
[vim]: http://www.vim.org
[ís]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/ís.mp3
[minn]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/minn.mp3
[ást]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/ást.mp3
[tré]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/tré.mp3
[ek]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/ek.mp3
[dró]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/dró.mp3
[sofa]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/sofa.mp3
[grœn]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/grœn.mp3
[øx]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/øx.mp3
[ǫl]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/ǫl.mp3
[hǫll]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/hǫll.mp3
[k1]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/kunna.mp3
[kyn]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/kyn.mp3
[mæla]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/mæla.mp3
[m]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/mɛːla.mp3
[nær]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/nær.mp3
[n]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/nɛːr.mp3
[spýta]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/spýta.mp3
[þat]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/words/þat.mp3

There is no short counterpart of æ /æː/ or long counterpart of ǫ /ɔ/. Both sounds
existed at one time, but in the kind of Old Norse on which the normalised
spelling is based short /æ/ had coalesced with e and long /ɔː/ with á. The use
of œ to denote the long equivalent of ø is an arbitrary convention, and in some
works ǿ is found. Note that Old English Orthography, uses "oe" for this sound.

Most of these sixteen distinctive vowels occur exclusively in stressed
syllables. In unstressed syllables there is no distinction of length and
for the most part a basic three-way contrast is found between a, i and
u. Some uncertainty exists about how these unstressed vowels were
pronounced, but the student will be safe enough using the following.

Unstressed vowels:
-----------------

RULE: p_vUnstressed_i - Unstressed i is opened, as in the 'y' of city  
RULE: p_vUnstressed_u - Unstressed u, as in the 'oo' of wood or good  

        Notes:

        The symbol below the IPA for i, looks like a captal T, it is the
        lowering diacritic, indicating that the sound is a true mid-vowel, or
        more opened than without the diacritic.

Vowel | IPA | X-Sampa | Description                                | Example word  
----- | ----| ------- | ------------------------------------------ | ------------------  
ᚨᛅᚪ a | [a] | a       | same as stressed a                         | leysa ‘(to) release’  
  ᛁ i | /̞i/ | _oi     | [:sound:as the y in English 'city'][city]  | máni ‘moon’  
  ᚢ u | [ʊ] | U       | [:sound:as in English 'wood'][good]        | eyru ‘ears’  

[city]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/i_as_in_city.mp3
[good]: https://secure.jerkface.net/~jim/OldNorseHub/sounds/u_as_in_good.mp3


Dipthongs:
----------

RULE: p_vDip_ei - ei, the 'ay' of bay  
RULE: p_vDip_ey - ey, ON e + y, /ø̯y/ or /ɛ̯y/  
RULE: p_vDip_au - au, as the 'ow' in English: now  

        Notes:

        The inverted breve underneath a vowel in IPA
        indicates that it is not syllabic. Each dipthong
        is only one syllable.
        
        The second pronounciation for ey is for a later period than the first.

        I am having an issue where the diacritic shows up on the first letter
        on the web, but on the second one in my source. I intend it to be on
        the second letter.

       

Vowel | IPA               | X-Sampa | Description           | Example words  
----- | ----------------- | ------- | ----------------------| ------------------  
au    | [a̯u]              | }_^u    | as in English now     | lauss 'loose'  
ei    | [ɛ̯i]              | E _^i   | as in English bay     | bein  'bone', [nei][nei] 'no', [heim][heim] 'home'  
ey    | [ø̯y], [ɛ̯y]        | 2_^y    | ON e + y              | hey   'hay', [Freyja][Freyja]  

[nei]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/nei.mp3
[heim]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/heim.mp3
[Freyja]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/ey_Freyja.mp3

Old Norse Consonants (Reconstructed)
===================================

RULE: p_cFisV - f is [v] if folowed by a vowel or a voiced consonant, unless it is the first letter of the word.  
RULE: p_cGGorNGbeforeSorT - g becomes [k] when preceded by n or g and followed by s or t  
RULE: p_cGinsideWord - g becomes [ɣ] when inside a word, unless followed by s,t,j, or i  
RULE: p_cGinsideWordST - g becomes [x] inside a word before s or t  
RULE: p_cGinsideWordJI - g becomes [ʝ] inside a word before j or i  

consonant | context                    | ipa | x-sampa | examples                                 
--- | ---------------------------------    | --- | --- | -----------------------------------------
f ᚠ | at beginning of word, or             | [f] | f   | [falla][falla] 'fall'                    
    | before a voiceless consonant         | [f] |     | [haft][haft] 'have'                      
    |                                      |     |     |                                          
f ᚡ | otherwise. (ᚡ)                       | [v] | v   | [hafa][hafa] 'have', [hef][hef] 'have'   
    |                                      |     |     |                                          
g ᚵ | beginning of word, or                | [g] | g   | [ganga][ganga] 'walk'                    
    | ng, not before s or t, or            | [g] |     |                                          
    | gg, not before s or t                | [g] |     | [Frigga][Frigga] 'Frigga'                
    |                                      |     |     |                                          
g ᚴ | gg or ng, before s or t              | [k] |     | [eggs][eggs]                             
    |                                      |     |     |                                          
    | inside a word, not before s,t,j,or i | [ɣ] | G   | [saga][saga] 'story', [dag][dag] 'day'   
    |                                      |     |     |                                          
    | inside a word, before s or t         | [x] | x   | [dags][dags], [sagt][sagt]               
    |                                      |     |     |                                          
    | inside a word, before j or i         | [ʝ] | j\  | [segja][segja]                           

 ... Under Construction ...  

[ɣ]: http://en.wikipedia.org/wiki/Voiced_velar_fricative
[ʝ]: http://en.wikipedia.org/wiki/Voiced_palatal_fricative
[falla]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/
[haft]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/
[hafa]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/
[hef]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/
[ganga]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/
[Frigga]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/
[eggs]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/
[saga]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/saga.mp3
[dag]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/dag.mp3
[dags]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/dags.mp3
[sagt]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/sagt.mp3
[segja]: http://secure.jerkface.net/~jim/OldNorseHub/sounds/words/segja.mp3


consonant | English sound                   | Context
----- | ------------------------------------- | -------------------
b   ᛒ | as in English 'Buy'
      |                                       |
bb    | as above, but longer
      |                                       |
d   ᛞ | as in English 'Day'
      |                                       |
dd    | as above, but longer
      |                                       |
f  ᚠ  | as in English 'Far'                   | Beginning of word
      | as in English 'Very'                  | otherwise
      |                                       |
ff    | as 'Far' but long
      |
g ᚷ ᚸ | as in English 'Goal'
      | as in Scots 'loCH'
      | as in Scots 'loCH' but voiced
      |
gg    | 'Goal' but long
      | as in Scots 'loCH' (alt English 'aCt') | before s or t
      |
h ᚺᚼᚻ | as in Englsh 'Have'
      |
j ᛃ ᛄ | as in English 'Year'
      |
k ᚲᚴᛣ | as in English 'Call'
      | same (alt Scots 'loCH')                | before s or t
      |
kk    | as above, but longer
      | same (alt Scots 'loCH')                | before s or t
      |
l  ᛚ  | as in English 'Leaf'
      |
ll    | as above, but longer
      |
m   ᛗ | as in English 'home'
      |
mm    | as above, but longer
      |
n   ᚾ | as in English 'siN'
      | as in English 'siNG'                   | before g or k
      |
nn    | as 'siN' but long
      |
p     | as in English 'haPPy'
      | same (alt English 'Far')               | before s or t
      |
pp    | as above, but longer
      | same (alt English 'Far')               | before s or t
      |
r     | rolled, as in Scottish English
      |
rr    | as above, but long
      |
s     | as in English 'thiS'
      |
ss    | as above, but long
      |
t     | as in English 'boaT'
      |
tt    | as above, but long
      |
v     | as in English 'Win'
      |
þ     | as in English 'THin'
      |
ð     | as in English 'THis'
      |
x     | two sounds, as in Scots loCHS
      |
z     | two sounds, as in English 'biTS'
