 # yalavarthi_assignment2
 # ruthvik bhairav yalavarthi
 # hyderabad
 > hyderabad is the capital city of telangana. It has many tourists places like salarjang museum
   charminar and also multiple diversity of cultures


 *****
Directions
 1. > going from maryville to kansas city 
       2. > left to park avenue 
       3. > from there take right at illinois route 
4. go straight line forward

******
un-ordered-list
* GO to hyvee
* take groceries
    * rice
    * plum cake
    * chicken 
    * vegetables
 * return back to home   
 ------------------------
![Delete](C:\Users\S545261\Documents\GitHub\assignment2-yalavarthi\sachin.jpg).
 [page](AboutMe.md) ** local to the repo.


 *******
 food-products
 1. the drinks are important to health<br>
 2.  also drinks keep body clean<br>
  | item | location | price |<br>
  | ------| ---------|-------| <br>
  | pepsi |  maryville | 50$ |<br>
  | limca | new york   | 25$ |<br>
  | frooti| illinois   |40$|<br>

*****************

## Pithy Quotes

As Grace Hopper said:

> We're living the future so the present is our past.

> I’ve always been more interested

---
## Code Fencing

*Aho–Corasick algorithm* form *String Processing* 

> In computer science, the Aho–Corasick algorithm is a string-searching algorithm invented by Alfred V. Aho and Margaret J. Corasick. 
> It is a kind of dictionary-matching algorithm that locates elements of a finite set of strings (the "dictionary") within an input text. 
> It matches all strings simultaneously. The complexity of the algorithm is linear in the length of the strings plus the length of the searched text plus the number of output matches. 
> Note that because all matches are found, there can be a quadratic number of matches if every substring matches (e.g. dictionary = a, aa, aaa, aaaa and input string is aaaa).

Aho–Corasick algorithm [Reference_link](https://en.wikipedia.org/wiki/Aho%E2%80%93Corasick_algorithm)

code for Aho–Corasick Algorithms

void add_string(string const& s) {
    int v = 0;
    for (char ch : s) {
        int c = ch - 'a';
        if (trie[v].next[c] == -1) {
            trie[v].next[c] = trie.size();
            trie.emplace_back();
        }
        v = trie[v].next[c];
    }
    trie[v].leaf = true;
}


Aho–Corasick algorithm [Code_link](https://cp-algorithms.com/string/aho_corasick.html)
