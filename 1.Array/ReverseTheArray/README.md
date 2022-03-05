
## Approach

Example
```bash
  README
```
we will initialize a new variable of type string 's' that will store the reverse of "README".
```bash
  string s=''
```
Now with the help of for loop of lenght string.lenght() from string.lenght()-1 to 0
```bash
 s=s+givenString[index]
```
## Time Complexity
```bash
 for(int i=str.length()-1;i>=0;i--){
      
      reverse=reverse+str[i];
    
  }
```
As we are doing some const number of operation for n times so time Complexity will be **O(n)**

## Space Complexity
```bash
 string reverseWord(string str){
    
   string reverse = "";
  int count=0;
  
  for(int i=str.length()-1;i>=0;i--){
      
      reverse=reverse+str[i];
    
  }
  return reverse;
 
}
```
As we are creating a vraible reverse so space Complexity depend on the length of string i.e. **O(n)**