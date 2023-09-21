# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown makes it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblock whenever possible.

Because it allows otheers to copy and paster their codes, to replicate their codes or research issues.


```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

if number < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(number)
  puts "The factorial of #{number} is #{result}."
end
```
