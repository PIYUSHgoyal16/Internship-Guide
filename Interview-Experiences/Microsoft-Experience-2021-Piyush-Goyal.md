#### Round 1
Coding Round on Mettl. People above 8 CGPA (later 7.9 after lot of efforts by CnP) were allowed to sit. 41 students were selected. 
Question Set same as <a href="https://discourse.iitmandi.co.in/t/microsoft-internship-interview-experience-2021-kartik-kathuria/475">Kartik Kathuria</a>.

#### Round 2
Interview Round on Microsoft Teams. Same as <a href="https://discourse.iitmandi.co.in/t/microsoft-internship-interview-experience-2021-kartik-kathuria/475">Kartik Kathuria</a> and 15 others.

#### Round 3
Interview Round on Microsoft Teams.
**Ques 1** <a href="https://www.interviewbit.com/problems/identical-binary-trees/">Write Function to know if two Binary Trees are Identical.</a>
**Ques 2** Given a matrix containing:
* 0 = denoting blank space
* 1 = unaffected person
* 2 = COVID positive person
Given that a affected person affects his neighbours, find the time required to affect the complete matrix.

I cleared what neighbour means, she mentioned that she meant all the eight adjacent cells. Then I mentioned it might be possible that some person remains unaffected. She asked for an example, I gave and she said great, you need to return -1 in this case.

Since time was less, I started with most Optimised solution using Graphs, but she said try to do it with arrays. I did it by traversing the matrix until someone remains unaffected and proved how the complexity of code is O(N^3). She was more than satisfied and I was promoted to the next round.


#### Round 4
Interview Round on Microsoft Teams. 

I was asked about my interests and Community Bridge Project. Questions were asked about what is my favourite subject and why is it so. Only one DSA question asked.

**Ques** 
Make a phone directory shoeing names and numbers of people based on the prefix entered by the user.

**Solution**
Store the contacts in an HashMap having name as key and number as value. Now the problem reduces to string matching.

I started with brute force string matching having Complexity O(N*M) where 
N = number of strings
M = length of prefix

Then arrived at <a href="https://www.youtube.com/watch?v=AXjmTQ8LEoI">Trie</a>. Explained her about insertion and update in an Trie. She was happy and asked if I could code it.

I took the challenge(never coded Trie before) but was successful. She stated that she was satisfied and asked if I had some doubts. We discussed her ongoing projects and the interview ended, landing me an intern at Microsoft.

### Tips
* #### Preparation
    1. **Interview Bit is a must.**
        No matter how good at Competitive Programming you are, there are always a standard set of problems that require a predefined method to solve them. Interview Bit being a small set helps to achieve this task in a short span efficiently.
    
    2. **Preparation Order**
        * Interview Bit (atleast 2 times)
        * Subjective knowledge (Database practicum, DSA ans OOPS)
        * Resume (Projects and Languages)
        * GFG (try to solve 10-20 problems of each subtopic)
        * LeetCode ( As the set is huge, don't worry if you can't solve it all :-) )
        * Competitive programming (only neccessary for CodeNation and DE Shaw)
        
    3. **Higher the CG, more are the chances of Selection.** Besides Shortlisting, Since only 2-3 problems are given to such a large batch, it might happen that most of you have solved exactly same number of problems and same number of test case. But the one having higher CG will be preffered in this case.

    4. **Write the answers to basic questions like Introduction, Vision, Why you love the company, etc and memorise them beforehand.**

* #### Interview
    1. **Always Show Positive Outlook** At the start of every interview, you would be asked about your previous rounds. You don't know the result and most probably not even the current interviewer. So matter how the previous round went, Always say: *It was great and fun solving the problem. The interviewer was very kind to help me and devise a time and space efficient solution*

    2. **Never Stop Talking** Even if you are devising the solution, do discuss the approach with the interviewer. It ensures that he is able to see your thinking process, and you don't start coding the wrong approach, that will cost you time and ultimately the intern.

    3. **Don't arrive at the most efficient solution immediately** Even if you know the answer, never give the brute force solution at first. Show the interviewer that you are thinking and devising the solution on the spot :-D 

    4. **Never forget to ask Questions** The problem sometimes given is vague. Do ask doubts (not unneccessary though) and clear the problem. At the end, include some points from the PPT and frame a question beforehand to be asked.

    5. **Never Lose Hope** It may happen that only people from certain branch and gender are given precedance. Also, you might feel you should have been selected after solving all the problems. But never lose hope and remember **APNA TIME AAYEGA**
