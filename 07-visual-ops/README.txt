Chapter 7: Advanced visual operations

With a region selected via one of the visual modes (charwise, block, linewise), 

r{char} replaces the entire selection.

U capitalizes everything, u makes everything lowercase.

In blockwise, I inserts text in front of every line, A inserts at the end, ESC applies the change

Use < or > to shift entire row by indent width (can prefix this for repeats).

for i in range(5):
    print(i)
        print(A[i])
        if (A[i] == i):
        break

Typing : uses the selected region as the range for the next command-line command.

DON'T CHANGE ME 
DON'T CHANGE ME 
DON'T CHANGE ME 
DON'T CHANGE ME 
CHANGE ME 
CHANGE ME 
CHANGE ME 

Use :norm to apply a normal mode command on each line, useful to repeat a small edit across many lines.
