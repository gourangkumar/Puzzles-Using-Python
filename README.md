# Puzzles-Using-Python
Interesting Solutions to Puzzles via Python!

# Recursive Python function to solve tower of hanoi 


def Tower-of_Hanoi(n, from_tower, to_tower, aux_tower): 
	if n == 0: 
		return
	Tower-of_Hanoi(n-1, from_tower, aux_tower, to_tower) 
	print("Move disk", n, "from tower", from_tower, "to tower", to_tower) 
	TowerOfHanoi(n-1, aux_tower, to_tower, from_tower) 


# No. of towers 
N = 4

# A, C, B are the name of towers 
Tower_of_Hanoi(N, 'A', 'C', 'B') 

