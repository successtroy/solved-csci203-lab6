Download Link: https://assignmentchef.com/product/solved-csci203-lab6
<br>
<ul>

 <li>To be able to do hashing with chaining</li>

 <li>To be able to read from file</li>

 <li>To practice writing solutions to problems in a clear and succinct way</li>

</ul>

<h1>Problem</h1>

Hash tables are very common in practice when you have a lot of insertions, deletions and search operations. We have seen that under the assumption of uniform hashing, collision resolution by chaining is used. You are to implement a simple hash table. Your program will prompt for the name of an input file, read and process the data contained in this file. The file contains a sequence of integer values. Read them and construct a hash table using chaining. You may use dynamic data for chains greater than one in length, but the majority of the dictionary should be an array of hash nodes.




Read each integer in turn and calculate its hash value using mod 100 as the hashing function. Thus, is if the key is k, the hash value h(k) = k mod 100.




When you have finished calculate:

<ol>

 <li>The number of empty entries in the hash table.</li>

 <li>The length of the longest chain.</li>

</ol>


