Download Link: https://assignmentchef.com/product/solved-cecs-529-homework-3
<br>



<ol>

 <li>Given the document Sally and Harry watched When Harry Met Sally before they ate popcorn, how many tokens are in the document? List all of the document types. List all of the terms assuming lowercasing and Porter stemming.</li>

 <li>From the course textbook, do problem 2.1 (at the end of chapter 2.2). Explain each of your answerswith one or two sentences.</li>

 <li>Suppose you want to index the body of a web page as a document. As discussed in class, you do notwant tokens like &lt;html&gt; or other markup tags to appear in the index. Write a paragraph about what text-processing strategies you would use to index an HTML le. Include the following:

  <ul>

   <li>How you would determine which tokens to ignore;</li>

   <li>How you would identify the actual content of the page (the part you want to index);</li>

   <li>How you would extract the title of the document (which might not be the same as the name ofthe le).</li>

  </ul></li>

 <li>Implement parts of a simple inverted index similar to the term-document index you implemented inHomework 1. Download the le Homework3Files_Java.zip or Homework3Files_CSharp.zip depending on whether you want to complete this lab in Java or C#.

  <ul>

   <li>Create a new project and add all four les from the zip     le to the project.</li>

   <li>Spend some time familiarizing yourself with the project as-is. It contains these les:

    <ol>

     <li>TokenStream: an interface for classes that can return a sequence of tokens from a le of text.</li>

     <li>SimpleTokenStream: implements the TokenStream interface to provide a stream of tokenswith minimal processing, by removing non-alphanumeric characters and lowercasing each token.</li>

    </ol></li>

  </ul></li>

</ol>

<ul>

 <li>NaiveInvertedIndex: a simple inverted index class. Each string term is mapped to a list ofinteger document IDs through an appropriate hashtable data structure.</li>

</ul>

<ol>

 <li>SimpleEngine: an application that reads a directory of text les and indexes them into the NaiveInvertedIndex, then prints the index.</li>

</ol>

<ul>

 <li>Fill in all TO-DO items in NaiveInvertedIndex and SimpleEngine. You do not need to touchTokenStream or SimpleTokenStream.</li>

 <li>Complete main method in SimpleEngine as in Homework 1, so that after indexing all documents,you allow the user to search for single terms and output the set of documents which contain that term.</li>

</ul>

1