# Include Order
Make sure to include line breaks between each group below.

Header files:

    1. Intra-Lib Includes
    2. Standard library
    3. Dependencies

Implementation files:

    1. Accompanying .hpp file
    2. Intra-Lib Includes
    3. Standard library
    4. Dependencies

# Naming
Language: American English

## Functions
    firstSecondLast()

    first()

## Class types
    struct StructName

    class ClassName

# Indent style
## Functions:
    func() {
        code();
    }

## Structs/classes:
    class X {
        classstuff
    }

## Control flow statements:
    if (x) {
        multi();
        line();
    }
    else {
        multi();
        line();
    }

<br>

    if (x)
        single();
    else
        line();

<br>

    switch (x) {
    default:
        code();

    case a:
        code();

    case b:
        code();
    }

## Loops:
    for(blah; blah; blah) {
        multi();
        line();
    }

    while(x) {
        multi();
        line();
    }

<br>

    for(blah; blah; blah)
        singleLine();

    while(x)
        singleLine();
