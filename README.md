# overthewire-challenge

```

bandit0-> NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
bandit1-> rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
bandit2-> aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
bandit3-> 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
bandit4-> lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
bandit5-> P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
bandit6-> z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
bandit7-> TESKZC0XvTetK0S9xNwm25STk5iWrBvP
bandit8-> EN632PlfYiZbn3PhVK3XOGSlNInNE00t
bandit9-> G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
bandit10-> 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
bandit11-> JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
bandit12-> 




cat data.txt | sort | awk 'NR==1 {prev=$0} NR>1 
&& $0==prev {count++} NR>1 
&& $0!=prev {if(count==0) 
print prev; prev=$0; count=0}
END
{if(count==0) 
print prev}'


```
