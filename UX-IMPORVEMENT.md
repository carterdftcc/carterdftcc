# [AmazoBot 1.0] Improvement Report

## The Single Change
"I changed the level of grumpiness  from AmazoBot 1.0 Grumpy Veteran to AmazoBot 1.0 Sternly Sage"

## Why THIS Change?
AmazoBot had more things to say that were not related to the actual question. This was a distraction.

## Test Results

### Test Case 1: What specific friction point ruins the experience?
- **Before:** AmazoBot provided the terms but never defined them. The rest of the output was related to provide insults.
- **After:** Amazobot was a little nicer but the terms were never defined.
- **Verdict:** No real improvement.
- **Screenshot:**
  
 https://github.com/carterdftcc/carterdftcc/blob/main/screenshot/test_case_1_before.png
 https://github.com/carterdftcc/carterdftcc/blob/main/screenshot/test_case_1_after.png
 

### Test Case 2: What specific friction point ruins the experience?

- **Before:** Asked for a comparison between two terms and was informed that the query was too vague.
- **After:** Received a similar answer but was told to rephrase the question.
- **Verdict:** Not much better. At least, I was asked to rephrase the question.
- **Screenshot:**
 https://github.com/carterdftcc/carterdftcc/blob/main/screenshot/test_case_2_before.png
 https://github.com/carterdftcc/carterdftcc/blob/main/screenshot/test_case_2_after.png
 
 
### Test Case 3: What specific friction point ruins the experience?
- **Before:** At this point, I am beginning to think that I am the problem, so I asked for a definition. I believed that I asked for the definition of a worm, but I received an answer about Cybersecurity.
- **After:** Now I know it is me.  I still receive a definition of the term Cybersecurity.
- **Verdict:** Just another version of the same, I will say Worse.
- **Screenshot:**
 
https://github.com/carterdftcc/carterdftcc/blob/main/screenshot/test_case_3_before.png
https://github.com/carterdftcc/carterdftcc/blob/main/screenshot/test_case_3_after.png

## Unintended Consequences
[What new problems did your fix create? Be honest!]
Mean and grumpy may come in degrees, but it is still mean and grumpy. Trying to dial it down seems to be an artform that I have not mastered. I used a third instance of Gemini to ask my questions as a benchmark, and it answered them well. The problem still exist, but in a different flavor.

## Still Broken (On Purpose)
Referring to itself in the third person is fun. So, I left that alone. Providing the answer from the perspective of 30+ years of experience. I felt nostalgic and wanted to relive my younger days. I was once called incorrigible, and I wanted to hear what it sounded like. Now, I understand why people don’t like it, but its part me, so it is a part of AmazoBot.

## Lesson Learned
It is easier to start over, but small adjustments require finesse and insight to see what they actually impact.
