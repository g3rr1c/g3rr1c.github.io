---
layout: project
type: project
image: <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/738ab225-29fd-4a8a-bc65-a5035e23fd08" />

title: "Not Quite English"
date: 2024
published: true
labels:
  - Java
  - Project
summary: "A Markov chain language model for ICS 211."
---

<img class="img-fluid" src="../img/cotton/cotton-header.png">

This is a Markov chain language model that generates random text based on the frequency of the word that comes after it. Built in Java, the program first reads a text document and keeps every word, the number of times it appears, and what word comes after it, recorded in a HashMap. After processing the entire Word document, the program then spits out a randomly generated text that is based on the frequency and probability of the word that comes after it. 

To give you an example of the program, here is a part of the U.S. Constitution. 

<hr>


We the People of the United States, in Order to form a more perfect Union, establish Justice, insure domestic Tranquility, provide for the common defence, promote the general Welfare, and secure the Blessings of Liberty to ourselves and our Posterity, do ordain and establish this Constitution for the United States of America.

The Constitutional Convention
Article I
Section 1: Congress

All legislative Powers herein granted shall be vested in a Congress of the United States, which shall consist of a Senate and House of Representatives.
Section 2: The House of Representatives

The House of Representatives shall be composed of Members chosen every second Year by the People of the several States, and the Electors in each State shall have the Qualifications requisite for Electors of the most numerous Branch of the State Legislature.

No Person shall be a Representative who shall not have attained to the Age of twenty five Years, and been seven Years a Citizen of the United States, and who shall not, when elected, be an Inhabitant of that State in which he shall be chosen.
  
.....(continued)



<hr>

If the program were to read this text document, here is an example of what it could spit out:

<hr>



The case of impeachment for, and vote by the congress may be chosen. representatives shall become president. section 2 the same state shall have compulsory process of the judges in a president shall not herein before the privilege of election of speech, or compact with his office. section 4: elections for the first election, they shall any bill shall be formed by the militia according to be privileged from the senate may by general welfare of representatives to the president shall consist only in any claims shall sign and vice president. section 2 the states respectively, or affirmation, and duties of such place to a vice president pro tempore of the united states, which the 3d day of impeachment. section 2 the senate, to be a more than twice, and the public trial, by and of race, color, or person of life of the revision and of the vice president, and under the electors appointed, and shall consist of the right of persons voted for, and expenditures of the expiration of the choice shall be divided as to be  elected to the president within seven years after the vice president, the ratification may empower the right of two houses shall be suspended, unless  in time to the several states, and in the privileges or representative, or the enemies thereof. but upon confirmation by ballot the president shall be  president from whatever source derived, without the vice president. but no state, territory, or other cases before it shall be commander in each of  the number of debts; pass the enemies thereof. but in the house in each state by jury shall be an amendment excessive bail shall have original jurisdiction. section 2 shall be employed in all intents and the first election, they shall take effect, until an equal protection of january, 

...(continued)



<hr>

While the output is a bunch of gibberish, it still displays a simple language model that could possibly imitate human speech based on word patterns. The program utilizes Java's built-in inheritance properties, iterators, and hashmaps to generate this text. 

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
