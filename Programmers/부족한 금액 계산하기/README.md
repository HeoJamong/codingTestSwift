```swift
import Foundation

func solution(_ price:Int, _ money:Int, _ count:Int) -> Int{
    var answer:Int = 0
    var total:Int = 0
    for i in 1...count{
        total += price*i
    }
    if(money-total<0){
        answer = abs(money-total)
        return answer
    }
    else{
        return 0
    } 
}
```