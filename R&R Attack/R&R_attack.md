# **RELAY_&_REPLAY Attacks**


>- ### A relay attack ia a technique related to man-in-the-middle and replay attacks. In a classic man-in-the-middle attack, an attacker intercepts and manipulates communications between two parties initiated by one of the parties. In a classic relay attack, communication with both parties is initiated by the attacker who then merely relays messages between the two parties without manipulating them or even necessarily reading them.

>- ### A replay attack is a type of attack where the attacker captures and replays a valid message or data stream that was previously sent between two parties. The attacker may capture the message or data stream and replay it at a later time, or the attacker may intercept the message or data stream and replay it in real time.
    

     

****      
## _KEY FOB ATTACK_
****
     When you push the door unlock button on your key fob, it sends out a modulated radio signal that gets picked up by a receiver in the car. If the modulated code matches the car’s, then it will unlock. But that would be incredibly easy to hack without any additional security. All a black hat hacker would need to do is record the radio signal and then play it back later — a classic replay attack

     To overcome that possibility, modern key fobs uses a rolling code system. Each time we push the unlock button, the key fob uses an algorithm to generate a new code. The car knows the same algorithm, and the old codes are discarded each time a new one is generated.

>The problem with this system is that the algorithm is not very secure. It’s based on a simple XOR operation, which is a very weak encryption algorithm. It’s so weak that it can be broken in a matter of minutes. The algorithm is also not very random, so it’s possible to predict the next code. 

>**The solution is to use a more secure algorithm, such as AES, and to make the algorithm more random.**

     Example of Key Fob  Attack
***
>     Jhon Wick attack by /** SAMY KAMKAR **/
>-    The John Wick attack works by recording and blocking the radio signal from the key fob. Because the signal was blocked, the car doesn’t unlock and the owner will naturally try again. That creates a second signal that is also recorded and blocked, but this time the attacker replays the first code to unlock the door. The owner is none the wiser, but now the attacker knows the next code in the sequence — which hasn’t yet been expired — and can use it to unlock the car and drive away.
***
