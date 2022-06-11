# interview-questions
Just a friend from Twitter interview questions.

# Interview Questions and Tips to Answer.

In the last 35 days, I have applied for Jobs in 15 different companies. Invited for interviews with 8, walked out from 3 companies in the middle. Given almost 20 rounds of interviews, cleared EVERY SINGLE ROUND.

Now, I have 4 offers in hand,1 Full Stack, and 3 Frontend roles. 1 pending.

**_I’m writing this document to share all the questions I faced in the interviews and some tips to answer them._**

  

### Company -1

**Role** - JavaScript UI Engineer, 1+ years of experience.

  

![](https://t37475729.p.clickup-attachments.com/t37475729/e767e2ce-53d9-47ab-82cf-a22f62ef475b/Screenshot%20from%202022-06-04%2012-26-30.png)

I applied to this role via [Naukri.com](http://naukri.com/) after verifying the job exists on their careers page. The whole interview process had 5 rounds in total, 4 tech rounds, and one HR. Let’s look at each round of the interview.

1.  **Online Assessment**

I got an online assessment link to be taken in the next 3 days. You can check the problem statement with the solution in the [Github repo here](https://github.com/Faheem-Khan97/javascript-coding-problems-with-theory/tree/main/DOM%20Challenges/challenge-1). ( Give it a star my friend ☺️ ).

  

1.  **Tech Interview with a Senior Engineer.**

The 2nd round was a face-to-face ( virtual ) interview. In this round, the interviewer introduced himself and asked about myself. After this, the actual interview started.

  

At first, the interviewer opened my solution for the online assessment and started asking about that. I had implemented `mouseenter` and `mouseleave` events to change the color of only vowels on hovering over the reversed text (Read the problem statement in the `index.js` file of the GitHub repo linked above ).

  

He asked me to delete those two JS events and do the same thing with CSS. I did that after a google search ( It was allowed lol ).

  

Then, we talked about **DOM manipulation** and why we shouldn’t do that in a loop. We also talked about other optimizations like **Debouncing and Throttling**. He didn’t ask me to implement though.

Next, the interviewer started asking me about various JavaScript concepts.

1.  1.  What is hoisting in JavaScript?
    2.  How `let` and `const` have affected the concept of hoisting. ( This was a follow-up to the previous question ).
    3.  What are closures and their use cases?
    4.  Shallow copy vs Deep Copy.
    5.  How to prevent an object from mutation. ( Basically freezing an object).
    6.  As I had mentioned **Next.JS** in my resume, he asked me benefits of using it.
    7.  Client-side rendering and Server-side rendering. ( Follow up question )
    8.  Next, he gave me a coding problem to solve. Check the problem statement with the solution in the [Github Repo here](https://github.com/Faheem-Khan97/javascript-coding-problems-with-theory/blob/main/interviews/problem-1.js). I solved the problem within a minute ( was quite easy ). He asked a couple of follow-up questions based on the solution.

The interview **ended** at this point. He asked me If I have any questions. I asked a couple of questions about the company then the call was dropped.

  

The next day, I received a call from HR and she told me I have cleared the interview and as a part of the next round of interviews, she shared a **take-home assignment** over email.

  

**3\. Take-home Assignment Round**

In the 3rd round of the interview, I got a take-home assignment. You can find assignment details shared by them in a [pdf file here](https://drive.google.com/file/d/1LpJeNMMJ7eV2MPTAh80O2AjIOpdrWsLG/view?usp=sharing).

  

I asked them for 10 days to complete this considering I have a full-time job. They agreed.

I submitted the solution in a private repo ( as asked ) and hear back from them after a week. They considered my solution good and proceed ahead to the next round.

  

**4\. Final Tech round with the Co-Founder.**

This was the longest interview I have ever taken. It lasted for 2:30 hrs. 2 hrs of interviews and 30 minutes of discussion about the company’s culture, values, and how they operate.

  

Again this interview started with an introduction. Then, he looked at my resume and asked the following questions -

1.  1.  What project you’re working on in the current company.
    2.  Why have you listed so many techs in your skill section? Do you really know them all?
    3.  I replied: I love to explore different techs that’s why they are so many. I’m well skilled in React, JavaScript, and Front-end development in general. Also, I have good enough knowledge of Back-end development using Node, Express, and MongoDB and I’m just starting out learning Next.JS + TypeScript. ( Interviewer looked Satisfied ).
    4.  You run a blog, right? Did you build this on your own and using what technologies.
    5.  I replied: I run a blog but I have not built it on my own and then I explained the supremacy of Hashnode. 😅

Next, he looked up my solution to the take-home assignment and cloned the repo, and run the app locally after installing the required dependencies. He tried and tested every feature and found everything was working fine. Then, he started asking questions —

1.  1.  Why have you used `useCallback` in your code?
    2.  What optimizations does React do?
    3.  I said: Virtual DOM, manipulation of DOM in an async way, and batching multiple state changes. He asked more, I replied: `code-splitting`. He said this is a webpack thing, not a React thing.
    4.  What is Synthetic event? Why not native events?
    5.  How would you implement your first assessment ( from round -1 ) in React?
    6.  He asked about how I implemented the shareable feature in the take-home assignment.
    7.  How does Redux data flow work?
    8.  Have you used any middleware in Redux? ( I talked about `redux-thunk` )
    9.  Have you used `redux-saga`?
    10.  I replied: No, but I told that I’m familiar with it.
    11.  What are generators in JavaScript?
    12.  There was some redundant code in the assignment solution. He asked me to remove that.
    13.  You have used `async-await` not promises why? Can you convert them to promises?
    14.  Have you ever used `React-Router`? ( There was a problem in my solution and it was related to routes that’s why he asked)
    15.  Do you have any exposure to backend languages or databases?
    16.  What are you learning currently?

This was all about this round. We discussed the company and culture afterward.

**5\. HR Round**

This was a very short call and the interviewer asked me about my previous company and why am I looking for a change. A few other simple questions were there too.

### Company -2

**Role** - Full Stack Developer, 1+ years of experience.

A recruiter approached me via [Naukri.com](http://naukri.com/) and asked about my availability for the job role and also asked about my expectations from the new company. The whole interview process had 3 rounds in total, 2 tech rounds, and one HR. Let’s look at each round of the interview.

1.  **First Tech Round with a Senior Engineer.**
    1.  Tell me about yourself.
    2.  Questions from my projects about Serverless, Firebase ( I had used these in my projects )
    3.  Find the 2nd largest element in an array. I used a naive approach first then he asked me to solve in `O(N)` complexity.
    4.  What is Node.JS?
    5.  What is a REST API? What are different HTTP methods?
    6.  Do you know anything about job scheduling?
    7.  What Node frameworks and databases ( Relational, Non-relational ) you have worked with?
    8.  ACID Properties in Database Management.
    9.  Any knowledge of AWS services? I talked about s3 and the process of uploading images and showing them in UI. At this point, He started asking JavaScript questions.
    10.  Explain Null vs Undefined in JavaScript.
    11.  Next, he gave me two output-type questions, one based on `this` and another on `promises`. There was an issue with `this` in the output question. Asked me how to resolve it.
    12.  Explain `this` and how its values can be changed at runtime.
    13.  I explained it in long detail. Almost a brief of [this blog](https://faheemkhan97.hashnode.dev/the-mysterious-this-keyword-lets-demystify-it). I also talked about the `call`, `apply`, and `bind` methods.
    14.  `for...of` loop vs `for...in` the loop. ( Now, React begins 🤪 )
    15.  What is React.JS?
    16.  I replied but in my definition, I didn’t mention Virtual DOM. He said I was looking for a specific keyword that is Virtual DOM.
    17.  What is virtual DOM?
    18.  What are the hooks you have used? Explain useCallback vs useMemo with use cases.
    19.  LifeCycle methods and how to kind of control the lifecycle of functional components?
    20.  `useEffect` v/s `useLayoutEffect`.

At this point, the interviewer got impressed with my ability to explain answers and ended the interview by saying “ You seem quite good at JS and React.”

  

1.  **Tech Round-2 With a Panel of Two Engineers.**

Again this round started with an introduction and then they asked me about my experience and expertise.

1.  1.  A quiz question involving multiple setTimeout, one of them with a delay of 0 ms. I told them the output.
    2.  Even if the delay is 0 ms in one of the setTimeout, why is it not executing immediately. ( I explained in detail with the Event loop, callback queue etc.)
    3.  Promise methods. `Promise.all()` vs `Promise.any()` vs `Promise.allSettled()` .
    4.  Coding Problem - Write poly-fill of `Promis.all()` .
    5.  Coding Problem - [Same as this](https://learnersbucket.com/examples/interview/execute-async-functions-in-series/). ( Took me around 20 minutes to solve)
    6.  Closures in JavaScript
    7.  Authentication and JWT. Refresh Tokens vs Access Tokens.
    8.  CORS policy.
    9.  UseEffect and reconciliation in React.
    10.  useCallback, useMemo and React.memo().
    11.  useRef and its uses.
    12.  Technical difference ( apart from syntax difference) between class-based components and functional components.
    13.  state management at a component level and at a global level. Redux vs Context API. Benefits of Redux.
    14.  GraphQL vs Rest.
    15.  Request-Response cycle in a client-server model. Where Middlewares fit in this request-response cycle.
    16.  Client-side vs Server-side rendering.
    17.  Could you please tell me about some ways to optimize a web application?

These were all of the questions. He asked a couple of things I have not heard of. SO I don’t remember to list it here.

**3\. HR Round**

She talked about company policies and asked me some questions about my previous company. Nothing much to share.

### Company -3

**Role** - Frontend Developer ( 1+ Years of Experience )

It had 3 rounds, 2 Tech, and 1 HR.

  

1.  **Online Assessment.**

The assessment consisted of 30 quiz questions and 2 coding problems to be solved using the React.JS library.

  

Quiz questions were easy/medium level from JavaScript and React.JS. The coding questions were pretty easy. The first task was to convert Celsius to Fahrenheit and vice-versa. We had two input fields, one for Celsius and the other for Fahrenheit. Change in any one of these two inputs should reflect in another. The 2nd question was just like a simple counter app with some twists.

  

1.  **Tech Round with the Tech Lead.**

Every time it starts with an Introduction. Next, he asked about my experience in the previous company. Technical questions start at this point -

1.  1.  Tell me some of the APIs introduced in HTML5. ( I remembered only 2)
    2.  Ways to store data on the client-side i.e. inside browsers.
    3.  Session Storage vs Local Storage.
    4.  CSS combinators. Child vs Descendant Selectors. ( Then he told me about siblings and adjacent sibling selectors).
    5.  How does the event loop work?
    6.  He gave me a coding problem. You can find a similar problem with the solution in my [Github repo here](https://github.com/Faheem-Khan97/javascript-coding-problems-with-theory/blob/main/recursiveProblems/flattenObject.js). Give that repository a ⭐ ( I’m saying it again 😆).
    7.  Lifecycle methods in class-based components. I explained a few and told about useEffect and functional components. ( He didn’t look satisfied)
    8.  The component has mounting, updating, and unmounting phases. Tell lifecycle methods of each of these phases. ( Answered partially)
    9.  What about `getDerivedStateFromProps` and `getSnapshotBeforeUpdate` methods?
    10.  How to achieve exact behavior like `componentDidUpdate` in functional components?
    11.  For the answer to this question, [read here](https://stackoverflow.com/questions/53255951/equivalent-to-componentdidupdate-using-react-hooks).
    12.  What is debouncing and throttling? Differences between them.
    13.  Code debouncing. ( I did this and he checked my solution in different ways ).

Ended the interview.

  

**3\. HR Round**

Similar questions like company -1. Nothing much to share.

### Tips to Answer Questions.

1.  Knowing a topic and explaining that in a good way are two different things. Try to get good at both.
2.  When you learn a certain topic, think about how would you answer if someone ask you about this topic. I’m not saying to memorize the answer but you should have an idea of what to cover in your answer.
3.  Make room for the interviewer to ask questions. ( I will tell you an example)
4.  Know when to stop and wait a couple of seconds for the interviewer to respond.
5.  In case of coding problems, think aloud. Explain your approach as you go.
6.  If you don’t know something, say that you have no idea. Please accept the fact that you ( or anyone) can never know everything.
7.  **Example -** In one of the interviews, I got a question on `this` keyword. I covered-
    1.  `this` in the global scope.
    2.  `this` inside a function ( different scenarios)
    3.  `this` inside arrow function and event listeners.
    4.  I also told the value of this can be altered at runtime using `call`, `apply`, and `bind`. ( It took me around 90 seconds and I stopped here and gave chance to the interviewer to ask counter questions).
    5.  Next, he asked me about the `call`, `apply`, and `bind` methods. ( and this is what I wanted).
