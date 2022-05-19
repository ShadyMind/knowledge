
**O(N^2):**
```perl
for i := 1 to N do
	begin
	max := A[i,1];

	for j := 1 to N do
		begin

		if A[i, j] > max
			then

			max := A[i, j]

	end;

	writeln(max);
end;
```
