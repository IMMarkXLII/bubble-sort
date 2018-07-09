# bubble-sort

```
  		for(int i = 0; i < arr.length - 1 ; i++) { 
			for(int j = i+1; j<arr.length  ; j++) { 
				if(arr[j] < arr[i]) { // for ascending order . for decending order change to arr[j] < arr[i]
					int x = arr[i];
					arr[i] = arr[j];
					arr[j] = x;
				}
			}
		}
```
