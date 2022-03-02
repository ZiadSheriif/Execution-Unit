# Execution Unit
<div align="center">
<img   width= 350px height =350px src="https://anniehuang926860638.files.wordpress.com/2018/10/alu.gif">
</div>

<hr style="background-color: #4b4c60"></hr>

## <img align= center width=50px height=50px src="https://user-images.githubusercontent.com/71986226/154075883-2a5679d2-b411-448f-b423-9565babf35aa.gif"> Table of Contents

- <a href ="#about"> 📙 About</a>
- <a href ="#use"> 💻 Get Started</a>
- <a href ="#Screenshots"> 📷 Demo Screenshots</a>
<hr style="background-color: #4b4c60"></hr>


## <img align="center"  height =50px src="https://user-images.githubusercontent.com/71986226/154076110-1233d7a8-92c2-4d79-82c1-30e278aa518a.gif"> About <a id = "about"></a>

<p>Using the simulation program (Altera Quartus), it is required to make an execution unit that
able to do the following commands:
<ul>
<li> Move Value to Register</li>
<li> Move Register to Register</li>
<li> Add Value to Register</li>
<li> Add Register to Register</li>
<li> AND Value to Register</li>
<li> AND Register to Register</li>
</ul>
</p>

<hr style="background-color: #4b4c60"></hr>

## <img  align="center" width= 60px height =50px src="https://c.tenor.com/Vbsu0tIL5DwAAAAi/peach-goma.gif"> How use the application  <a id ="use"></a>

<ol>
<li> Clone the repository

```
git clone https://github.com/ZiadSheriif/Execution-Unit
```

</li>
<hr>
<li> Main File is 

```
Execution-Unit/Execution Unit/ExecutionUnit.bdf
```
</li>
<hr>
<li>
How many commands does the execution unit have?
<p>
<b>6 commands:</b>
<br>
<ul>
    <li> Move Value to Register</li>
    <li> Move Register to Register</li>
    <li> Add Value to Register</li>
    <li> Add Register to Register</li>
    <li> AND Value to Register</li>
    <li> AND Register to Register</li>
</p>
</li>
</ul>
<hr>
<li>
How many bits are required for the user input command?
<p>
<b>10 bits:</b>

<table>
<tr><th>1.&ensp; [1..0] destination (00,01,10)</th> </tr>
<tr><th>2.&ensp; [3..2] source (00 A, 01 B, 10 C, 11 input)</th></tr>
<tr><th>3.&ensp; [5..4] operation (00 MOV ,10 ADD ,11 AND)</th></tr>
<tr><th>4. &ensp;[9..6] input</th></tr>
</table>
</p>
</li>
<hr>
<li>
How many forbidden input commands do execution unit have?
<p>
<table>
<tr><th>1. &ensp;[1..0]= `11` the input can’t be destination</th> </tr>
<tr><th>2. &ensp;[5..4]=`01` there is no operation</th></tr>
</table>
<b>EX:</b>&ensp; 1111010011 (invalid)
</p>
</li>
</ol>

<hr style="background-color: #4b4c60"></hr>


<!-- ## <img align= center width=50px height=50px src="https://media4.giphy.com/media/WvmddR1RGXyqDg2MmV/giphy.gif?cid=ecf05e471wxmxcpwvskpks2ztbvgu5111xo90mvqgq3ie1lc&rid=giphy.gif&ct=s"> Demo Screenshots <a id ="Screenshots"></a>

![image](https://user-images.githubusercontent.com/71986226/154477737-3ee9f702-c7d7-48b3-a7c9-81a4404fc420.png)

<hr>

![image](https://user-images.githubusercontent.com/71986226/154478022-cb72d049-a85b-4603-a0e1-936d51d89008.png)
<hr>

![image](https://user-images.githubusercontent.com/71986226/154478143-8ce3937b-8c9c-4f77-a769-9c5b7a4951b1.png)
<hr>

![image](https://user-images.githubusercontent.com/71986226/154477592-60f76602-c47a-4303-ae18-a0dd0b056865.png) -->


<!-- <hr style="background-color: #4b4c60"></hr>

## <img  align="center" width= 40px height =40px src="https://user-images.githubusercontent.com/71986226/154458911-a4ba9a44-a497-4d7e-a7b9-2340b51eeec4.gif"> Contributors <a id ="Contributors"></a> -->

<!-- <table >
  <tr>
     <td align="center"><a href="//https://github.com/ZiadSheriif"><img src="https://avatars.githubusercontent.com/u/71986226?v=4" width="150px;" alt=""/><br /><sub><b>ZiadSheriif</b></sub></a><br /></td>
  </tr>
</table> -->
