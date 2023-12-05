# love-local
love local assignment
def length_of_last_word(s):
    # Split the string into words
    words = s.split()

    # Check if there are any words in the string
    if not words:
        return 0

    # Return the length of the last word
    return len(words[-1])

# Test cases
print(length_of_last_word("Hello World"))  # Output: 5
print(length_of_last_word("   fly me   to   the moon  "))  # Output: 4
print(length_of_last_word("luffy is still joyboy"))  # Output: 6
