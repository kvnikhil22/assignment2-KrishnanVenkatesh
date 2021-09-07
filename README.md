# assignment2-KrishnanVenkatesh

# Nikhil KrishnanVenkatesh

###### London

One of the big reasons why London is my **favourite city** in the world is because of all of the **amazing memories** I have in London. London was the very first place where i started my first **film** and first trip to Europe. That trip totally changed my life and it meant a lot to be able to start it in London.
---
## Directions to travel from Maryvile to London :
1. Book online tickets to london heathrow airport from kansas city airport through airlines website
2. go to airport atleast two hours before.
3. If your not done with web-check go to respective flight Checkin counter and do inperson checkin.
4. go to secuity check and have a seat in flight.
5. After long journey you'll reach to the city of magic **London** Heathrow airport.

## Check-List to the trip :
* My personal DSLR camera 
* Drone
* Gimbal
* laptop
* snacks 
* Camping Tents
* Booked tickets confirmation letter (room,flights)
* cards

 ![AboutMe](./AboutMe.md)

 ---

 # Famous Food in Hyderabad

 Here's the list of few famous food items in Hyderabad which Hyderabadies love to have....!!!


|Items|Places|Prices|
| ----- | ----- | ----- |
| RamkiBandi |Nampally | Rs.100 |
| Burger | MCD | Rs.60 |
| chicken Biriyani | Paradise | Rs.500 |
| Veg Biriyani | awarchi RTC X-roads | Rs.250 |

---

### Quotes about Filmaking

> “The most honest form of filmmaking is to make a film for yourself.” - *Nikhil K V*

> “Everything about filmmaking tries to distract you from that first fine rapturous vision you have of the film.” - *Ted Kotcheff*.

---

### Algorithm

> Bipartite graph can be used in the medical field in the detection of lung cancer, throat cancer etc.

> Used in search advertising and e-commerce for similarity ranking.

> Predict movie preferences of a person.

> Stable marriage6 and other matching problems.

[Link for the source](https://www.educative.io/edpresso/what-is-a-bipartite-graph)

```
int n;
vector<vector<int>> adj;

vector<int> side(n, -1);
bool is_bipartite = true;
queue<int> q;
for (int st = 0; st < n; ++st) {
    if (side[st] == -1) {
        q.push(st);
        side[st] = 0;
        while (!q.empty()) {
            int v = q.front();
            q.pop();
            for (int u : adj[v]) {
                if (side[u] == -1) {
                    side[u] = side[v] ^ 1;
                    q.push(u);
                } else {
                    is_bipartite &= side[u] != side[v];
                }
            }
        }
    }
}

cout << (is_bipartite ? "YES" : "NO") << endl;

```

[Link for the algorithm source code](https://cp-algorithms.com/graph/bipartite-check.html)




