<div align="left">
<h1>
    <img alt="header" src="/src/assets/Header.png" width="800"></img>
</h1>
Welcome to A December of Algorithms (2021). After overwhelming responses from previous years, we present you with a new collection of algorithms to implement this December. Each Day, Each Algorithm ;) Finish them all to get a certificate :)

**Send a pull request only after completing all 31 algorithms.**

**Please submit all PRs on or before January 10th 11:59 PM IST.**

## What Do I Do?
We have a small collection of algorithms, one for every day of the month. Scroll down to take a look at them. All you need to do is fork this repository, implement all 31  algorithms and send a pull request over to us. Check out our FAQ for more information.

## Index
  - [**December 1 - Sherlock's Quest**](#december-1---sherlocks-quest)
  - [**December 2 - The Convo!**](#december-2---the-convo)
  - [**December 3 - Lotto!**](#december-3---lotto)
  - [**FAQ**](#faq)
  - [**Maintainers**](#maintainers)


## Algorithms

 ### December 1 - Sherlock's Quest
 
   #### Problem Statement
   - It's the final quest of Sherlock Holmes. The Moriarty wants Sherlock dead and is hiding behind a door on the same floor. To make sure he gets killed, Moriarty has filled all the rooms except the one he is in with poisonous gas.
   - The door number behind which he is hiding is designed in such a way that the sum of the left half and right half of the square of the number is equal to the number and is also a multiple of 3. 
   
   <p align="center"><img src="https://i.imgur.com/pIc2I8j.gif" height=250/></p>
   
   #### Sample Input/Output
   ```
    Room: 45
    Status: Safe 
   ```
   ```
    Room: 36
    Status: Not Safe
   ```
   #### Explaination
   ```
    45 is a multiple of 3
    45^2 = 2025
    20 + 25 = 45
   ```   
   
----
  
### December 2 - Bingo!
  
  #### Problem Statement
  - Your local community conducts a game night every Saturday and they want you to lead a game of Bingo this weekend. You must come up with numbers to be read out during the     game.
  - The numbers can be chosen on the basis of certain criteria:
  - Begins with a positive integer, sum of squares of digits must replace the number.
  - Continue until the number is 1 or loops interminably without including 1.
  - The numbers must end in 1 to be selected. 
  - Return ‘YES’ if the number is chosen, and ‘NO’ if not.

    <p align="center"><img src="https://i.imgur.com/O31uZDd.jpg" /></p>
  
  #### Constraints
   ```
  - 1<=n<=2^31-1
   ```
  
  #### Sample Input/Output
  ```
  Input: n=2
  Output: NO
  ```
  ```
  Input: n=19
  Output: YES
  ```

  #### Explanation
  ```
   1^2 + 9^2 = 82
   8^2 + 2^2 = 68
   6^2 + 8^2 = 100
   1^2 + 0^2 + 0^2 = 1

   ```   

### December 3 - Lotto!
  
  #### Problem Statement
  -In a lottery game , each participant  can choose a lucky board which is in the form of a 2D (x x y) grid. He/she can win the lottery if they are able to find their name on    the lucky board. Find whether a particular participant can win the game or not. Assume that there can be more than one winner who wins the lottery. 
  - Return true if the participant wins else return false
  ### Rules:
  - 1.The name of the participant has to be arranged in a sequentially adjacent manner.
  - 2.The  neighbouring alphabets can be horizontal as well as vertical
  - 3.Same alphabet cell cannot be used more than once while forming the name.
    
  
  ### Constraints
  ```
    x == board.length
    y = board[i].length
    1 <= x, y <= 6
    1 <= name.length <= 15
    board and name consists of only lowercase and uppercase English alphabets
```
  <p align="center"><img src="/src/assets/input1.png" /></p>
  
  #### Sample Input/Output
  ```
  Input: [["D","J","O","G"],["W","B","H","S"],["T","Z","N","E"]], name = "JOHN"
  Output: true
  ```
   <p align="center"><img src="/src/assets/input2.png" /></p>
   
   #### Sample Input/Output
  ```
  Input: [["L","N","A","C"],["W","B","A","D"],["T","Z","F","E"]], name = "DEV"
  Output: false
  ```

  #### Resources
  - [Backtracking](https://www.geeksforgeeks.org/backtracking-algorithms/)

---

## Maintainers

<table>
    <thead>
        <tr>
            <th><a href="https://github.com/bearlike">Krishnakanth</a></th>
            <th><a href="https://github.com/mahavisvanathan">Mahalakshumi</a></th>       
            <th><a href="https://github.com/mahavisvanathan">Mahalakshumi</a></th>       
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center"><a href="https://github.com/bearlike"><img width="64" src="https://avatars1.githubusercontent.com/u/39209037" alt="f"></a></td>
            <td align="center"><a href="https://github.com/mahavisvanathan"><img width="64" src="https://avatars2.githubusercontent.com/u/40058339" alt="f"></a></td>
            <td align="center"><a href="https://github.com/mahavisvanathan"><img width="64" src="https://avatars2.githubusercontent.com/u/40058339" alt="f"></a></td>
        </tr>
        <tr>
            <td align="center"> :hammer::construction::pencil: </td>
            <td align="center"> :hammer::construction: </td>
            <td align="center"> :warning::pencil: </td>           
        </tr>
    </tbody>
</table>

----

FAQ
======

#### Who can join the Challenge?
Anyone who is passionate about coding and can dedicate a little time a day for the challenge for the next 31 days.

#### When should I submit the pull request?
You don't need to submit it everyday. Just submit it once you're done with all 31 algorithms.

#### What if I'm not able to code every day?
Not a problem. While coding every day is nice, we understand that other commitments might interfere with it. Plus its holiday season. So you don't have to solve one problem every day. Go at your own pace. One per day or 7 a week or even all 30 in a day.

#### What language should I use to code?
Anything! New to GoLang? Best way to practice it. Wanna find out what all this hype about Python is? Use it! Any and all languages are welcomed. Maybe you could try using a different language for every problem as a mini-challenge?

#### Fork? Pull request? What is all that? I don't know how to use GitHub!
If you are new to Git or GitHub, check out this [small tutorial from our team](https://github.com/ASS-G/Git-Training-Kit) and [GitHub](https://guides.github.com/activities/hello-world/)

#### Where are the rest of the problems?
Our code ninjas are hard at work preparing the rest of the problems. Don't worry, they'll be up soon.

#### How should I complete these programs?
We have a folder for each day of the month. Simply complete your code and move the file into that folder. Be sure to rename your file to the following format: `language_username` or `language_username_problemname`
Some examples:
`python3_exampleUser.py`
`c_exampleUser.c`
**Please do not modify any existing files in the repository.**

#### I forked the repository but some problems were added only after that. How do I access those problems?
Not to worry! Open your nearest terminal or command prompt and navigate over to your forked repository. Enter these commands:
```bash
git remote add upstream https://github.com/SVCE-ACM/A-December-of-Algorithms-2020.git
git fetch upstream
git merge upstream/main
```
If you're curious, the commands simply add a new remote called upstream that is linked to this repository. Then it 'fetches' or retrieves the contents of the repository and attempts to merge it with your progress.
Note that if you've already added the upstream repository, you don't need to re-add it in the future while fetching the newer questions.

#### I received a merge error. What do I do?
This shouldn't happen unless you modify an existing file in the repository. There's a lot of potential troubleshooting that might be needed, but the simplest thing to do is to make a copy of your code outside the repository and then clone it once again. Now repeat the steps from the answer above. Merge it and then add your code. Now proceed as usual. :)

#### I'm facing difficulties with/need help understanding a particular question.
Open up an [issue](https://github.com/SVCE-ACM/A-December-of-Algorithms-2020/issues) on this repository and we'll do our best to help you out.

###### [[Back to Top]](#----)

![wave](http://cdn.thekrishna.in/img/common/border.png)
