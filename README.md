# Wiki_chatbot
Intelligent Wiki-Chat bot for querying Knowledge Graphs
The chatbot is capable of answering the following types of questions: 

1. Factual Questions

Factual questions can be answered based on the provided knowledge graph.

Example questions and answers: 

Who is the director of Good Will Hunting?	Gus Van Sant is the director of Good Will Hunting.
Who directed The Bridge on the River Kwai?	David Lean directed The Bridge on the River Kwai.
Who is the director of Star Wars: Episode VI - Return of the Jedi?	I think it is Richard Marquand.

2.  Embedding Questions

The TransE embeddings would be needed for answering embedding questions.

Example questions and answers: 

Who is the screenwriter of The Masked Gang: Cyprus?	The answer suggested by embeddings: Cengiz Küçükayvaz, Murat Aslan, and Melih Ekener.
What is the MPAA film rating of Weathering with You?	According to embeddings, the MPAA film rating of Weathering with You is PG-13.
What is the genre of Good Neighbors?	The genre of Good Neighbors is likely to be drama, comedy-drama, and comedy film.

3. Multimedia Questions

The provided multi-media dataset would be needed for answering multi-media questions.

Example questions and answers:

Show me a picture of Halle Berry.	https://www.imdb.com/name/nm0000932
What does Julia Roberts look like?	https://www.imdb.com/name/nm0000210
Let me know what Sandra Bullock looks like.	https://www.imdb.com/name/nm0000113

4. Recommendation Questions

Recommendation questions can be answered based on the provided knowledge graph.

Example questions and answers:

Recommend movies similar to Hamlet and Othello.	Adequate recommendations will be movies in the drama genre that are based on classic literature (e.g., Shakespeare, Dickens, or Jane Austen).
Given that I like The Lion King, Pocahontas, and The Beauty and the Beast, can you recommend some movies?	Adequate recommendations will be (2-D) animated movies or real-life remakes of Disney movies. 
Recommend movies like Nightmare on Elm Street, Friday the 13th, and Halloween.	Adequate recommendations will be horror movies from the 1970s or 1980s or sequels to the movies.

5. Crowdsourcing Questions

The provided crowdsourcing dataset would be needed for answering crowdsourcing questions.

Example questions and answers:

What is the box office of The Princess and the Frog?	The box office of The Princess and the Frog is 267000000.
[Crowd, inter-rater agreement 0.236, The answer distribution for this specific task was 2 support votes, 1 reject vote]
Can you tell me the publication date of Tom Meets Zizou?	The publication date of Tom Meets Zizou is 2011-01-01.
[Crowd, inter-rater agreement 0.040, The answer distribution for this specific task was 3 reject votes, 0 support votes]
Who is the executive producer of X-Men: First Class?	
The executive producer is Sheryl Lee Ralph.

[Crowd, inter-rater agreement 0.199, The answer distribution for this specific task was 2 support votes, 1 reject votes]
