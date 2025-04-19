# New_Repository

# Test

**Adam**

Adam = "Hi name is Adam"
print(Adam)


def try_parse_int(s, base=10, val=None):
    try:
        return int(s, base)
    except ValueError:
        return "error in processing the function"

print(try_parse_int("test"))
