# IMS EMBED

https://github.com/iiacobac/ims_wsd_emb

## Setup

* the file prop.xml should be completed wiht

<param name="dictionary_path" value="/path/to/dict"/>

* The files testFine.bash, test_one.bash, train_one.bash should be modified with the chosen parameters

<embeddingsPath> : path/to/embeddings
<WindowsSize> : tipically 10. Experiments made also with 5 and 20.
<Strategy CON, AVG, FRA, EXP> : Integration strategy, best results with FRA and EXP.


## Reference

This software is based in IMS (It Makes Sense) 

IMS (It Makes Sense) -- NUS WSD system
Copyright (c) 2010 National University of Singapore.

        Zhong, Zhi and Ng, Hwee Tou. 2010. It Makes Sense: A Wide-Coverage Word Sense Disambiguation System for Free Text. In Proceedings of the ACL 2010 System Demonstrations, pages 78--83, Uppsala,

========================

## Support

For more information, bug reports, fixes, please contact:
Ignacio Iacobacci
Department of Computer Science
Viale Regina Elena 295b 
Sapienza University of Rome
Rome, 
iacobacci[at]di[dot]uniroma1[dot]it
http://iiacobac.wordpress.com/

## License

IMS EMBED is an output of the MultiJEDI ERC Starting Grant No. 259234. IMS EMBED is licensed under a [Creative Commons Attribution - Noncommercial - Share Alike 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/) License.
