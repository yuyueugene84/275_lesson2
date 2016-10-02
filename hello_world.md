# Hello World!!!

```ruby
if operation == 1 #判斷式不成立，會接下去看下一個 elsif
  result = num1 + num2
  puts "your answer is: #{result}"
elsif operation == 2 #判斷式還是不成立，會接下去看下一個 elsif
  result = num1 - num2
  puts "your answer is: #{result}" 
elsif operation == 3 # 成立!，印出 num1 x num2 的結果
  result = num1 * num2
  puts "your answer is: #{result}"
else 
  result = num1.to_f / num2.to_f
  puts "your answer is: #{result}"
end
```