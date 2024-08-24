# Dat's First CS193 Homework
**Here is the list of some of my favorite things about CS193!**
- The instructor is super cool! He is still an undergrad, and he did a great job of teaching the lectures.
- No exam!!
- Terminal is just **"goat"**. I want to learn Terminal!
- $We \  will\  learn\  latex !!!!!$ $\int_{0}^{2\pi} \int_{0}^{2\pi} \int_{0}^{7} p \ sin(\phi) dp \  d \phi \ d \theta $.
- <details>
  <summary>I am terrible at formatting, so it is great to know that we will learn code formatting and coding standards</summary>
  
    ```cpp
      //CODING FORMAT!!!
      FOR(i,1,K)
      FOR(cap,0,Q)
          FOR(last,0,n)
                     FOR(mask,0,MASK(n)-1)
                  {
                      if(cap!=0)
     minimize(dp[i+1][0][0][mask],dp[i][cap][last][mask]+c[last][0]);
                      FOR(nxt,1,n)
      if(cap+d[nxt]<=Q&&BIT(mask,(nxt-1))==0)
     minimize(dp[i][cap+d[nxt]][nxt][mask|MASK()],dp[i][cap][last][mask]+c[last][nxt]);
                  }
  
                                      ||
                                      ||
                                      ||
                                   ---   ---
                                   \      /
                                     \   /
                                       \/
    for (int i = 1; i <= K; i++) {
        for (int cap = 0; cap <= Q; cap++) {
          for (int last = 0; last <= n; last++) {
            for (int mask = 0; mask <= (1 LL << (n)) - 1; mask++) {
              if (cap != 0) {
                minimize(dp[i + 1][0][0][mask], dp[i][cap][last][mask] + c[last][0]);
              }
              for (int nxt = 1; nxt <= n; nxt++) {
                if (cap + d[nxt] <= Q && BIT(mask, (nxt - 1)) == 0) {
                  minimize(dp[i][cap + d[nxt]][nxt][mask | (1 LL << (nxt-1) )], dp[i][cap][last][mask] + c[last][nxt]);
                }
              }
            }
          }
        }
    }
     //is not at the industry standard, but at least it is readable :D
    ```
    
    </details>
- Learn markdown because i'm bad at writing.
### That's it!

![Alt Text](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzBvM3c4bHRzcWFrbG52OHlueDFxem9zYW5maGNzcDQ1eGsxcjQwciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/uWlpPGquhGZNFzY90z/giphy.gif)
   
