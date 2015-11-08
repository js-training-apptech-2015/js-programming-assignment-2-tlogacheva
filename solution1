function solution1 (A) {
  A.sort(function(a,b) { return a-b; });
  var r = A[A.length-1]+1;
  
  for (var i=1;i<A.length;i++) {
    if (A[i] > 0) {
       if (A[i]-A[i-1] > 1) {
         r = A[i]-1;
         break;
       }
     }
    
  }

  
  return r;  
}

var A = [1,2,3,4,-3,-2,0];
document.write(solution1(A));
