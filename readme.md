puts "What is the total amount"
amount = gets.chomp.to_f
puts "What tip % you want to give? (Type 10, 15 or 20)"
tip_percent = gets.chomp.to_f
tip = amount * tip_percent/100
puts "How many people in your party: "
num_people = gets.chomp.to_f
puts "Your total with tip is : $#{'%.2f' % (amount + tip)}"
puts " Your share of the bill is: $#{'%.2f' % ((amount + tip)/num_people)}"
# amount = 10.5
# p '%.2f' % amount
puts "- Thank you for coming!-"
