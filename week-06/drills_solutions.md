#Drills Solutions


###Day 02 - Regular Expressions

```ruby
## Base Challenges

# 2. Write a regexp to match instances of "regex" in the text
/regex/

# 3. With the same test string, write a regexp to match instances
# of "regex", "regexp", or "regular expression".
/regex|regexp|regular expression/

# 4. Edit the regexp you just wrote to make sure it's case-insensitive
# (i.e. it should match "Regular Expression" as well as "regular expression").
/regex|regexp|regular expression/i

## Stretch Challenges

# 1. Again using the same text, write a regexp to match the HTML tags
# (`<p></p>` and `<span></span>`).
/<[a-z]+>|<\/[a-z]+>/

# 2. Write a regexp to validate a phone number.
/\A\d{3}(\s|-)\d{3}-\d{4}\z/

# 3. Write a regexp to validate an email address.
/[a-zA-Z0-9]+@[a-z]+.[a-z]+{2,}\z/

```

###Day 03 - Ruby Merge

Solution [here](https://github.com/sf-wdi-21/rubyMerge/tree/solution)

###Day 04 - Bubble Sort

Solution [here](https://github.com/sf-wdi-21/bubble_sort_ruby/tree/solution)
