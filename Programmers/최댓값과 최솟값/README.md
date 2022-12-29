```swift
func solution(_ s:String) -> String {
    
    var a = s.split(separator: " ")
    var array = [Int]()
    
    for i in a.indices{
        array.append(Int(a[i])!)
    }
    return "\(array.min()!) \(array.max()!)"
}
```