XLLM5 (Extreme LLM) has faster execution, smaller tables, simplified architecture, and better results, compared to the material in the <a href="https://github.com/VincentGranville/Large-Language-Models/tree/main/llm5">LLM5 folder</a>. 

Author: <a href="https://mltechniques.com/author/">Vincent Granville</a>. 

Python code:
<ul>
  <li><code>xllm5_util.py</code>: library with text processing functions, and to read the main tables</li>
  <li><code>xllm5_short.py</code>: main program for end-users, reads the tables produced by xllm5.py rather than creating these tables, and returns results to user queries (both on the screen and in a text file). </li>
  <li><code>xllm5.py</code>: main program for developpers, reads the crawled data, creates the tables, and returns results to user queries (both on the screen and in a text file)</li>
</ul>