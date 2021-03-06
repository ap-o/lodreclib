lodreclib - Linked Open Data Recommender Systems Library
=====================

lodreclib is a Java library to build recommendation engines fed by Linked (Open) Data datasets. It exposes methods to extract information from DBpedia or other RDF knowledge graphs via SPARQL queries and then to use it to train your LOD-based recommender system. lodreclib comes with the implementation of SPrank and two graph kernel methods as recommendation algorithms (see References). 

How to use
------------
Before running lodreclib, the `config.properties` file must be properly set. For more details about that configuration, see our [documentation](https://github.com/sisinflab/lodreclib/wiki).
The `config.properties` file provided in this repositoriy is set as an example using the Movielens dataset, whose files are in the movielens folder.

Using Maven, it is possible to build a runnable jar with the command 
~~~
mvn package
~~~
and is executable by the command
~~~
java -jar lodreclib-0.0.1-SNAPSHOT.jar 
~~~


References
------------
If you publish research that uses lodreclib, please cite it as
~~~
@Article{DOTD16, 
  author = {Tommaso {Di Noia} and Vito Claudio Ostuni and Paolo Tomeo and Eugenio {Di Sciascio}}, 
  title = "SPRank: Semantic Path-based Ranking for Top-N Recommendations using Linked Open Data", 
  journal = "ACM Transactions on Intelligent Systems and Technology (TIST)", 
  year = "2016", 
  note = "to appear", 
  url = "http://sisinflab.poliba.it/sisinflab/publications/2016/DOTD16" 
}
~~~
~~~
@Article{OODSD16, author = {
  Vito Claudio Ostuni and Sergio Oramas and Tommaso {Di Noia} and Xavier Serra and Eugenio {Di Sciascio}}, 
  title = "Sound and Music Recommendation with Knowledge Graphs", 
  journal = "ACM Transactions on Intelligent Systems and Technology (TIST)", 
  year = "2016", 
  note = "To appear", 
  url = "http://sisinflab.poliba.it/sisinflab/publications/2016/OODSD16" 
}
~~~
Credits
------------
This library was originally developed by Vito Mastromarino for his Master thesis at Polytechnic University of Bari under the supervision of Tommaso Di Noia, Vito Claudio Ostuni and Paolo Tomeo.

Contacts
------------
Tommaso Di Noia, tommaso [dot] dinoia [at] poliba [dot] it  
Paolo Tomeo, paolo [dot] tomeo [at] poliba [dot] it  
Vito Mastromarino, zlatanito88 [at] gmail [dot] com  
Vito Claudio Ostuni, vitoclaudio [dot] ostuni [at] poliba [dot] it  

