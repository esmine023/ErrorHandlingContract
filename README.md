# ErrorHandlingContract
This includes the METACRAFTERS edition

#  Error Handling Assessment

This repository is for the project assessment of the project of the last of my IT ELECTIVE Class for National Teacher's College for the solidity-vax-intermediate course of Metacrafters Academy. The purpose of creating this is to prove my learning and to showcase my skill as a solid developer to everyone!

# Requirements 
## Functionality
Contract successfully uses require()
Contract successfully uses assert()
Contract successfully uses revert() statements

## Explanation
Code read-aloud is submitted
Code read-aloud is complete (all steps explained)
Code read-aloud is clear and understandable

# Description
This code manages to tick the three requirements which are; revert(), require(), and assert() with a simple setValue and setting Nominator and Denominator that specifically determines a lot of queries and descriptions necessary to the progress it needed.

# Getting Started
This is the easiest and most efficient way to get through the Blockchain. Just get to https://remix.ethereum.org/. and get started with your token! Of course, it's not THAT easy. well just press the plus (+) button and you're good to code! (with minor adjustments like naming your file with .sol whichever you like) ()

'''

    function setValue(uint _value) public {
        require (_value > 0, "Value must be Greater than 0.");

        assert(_value != value);

        value = _value;
    }

    function performDivision(uint _numerator, uint _denominator) public pure returns (uint) {
        require(_denominator !=0, "Cannot divide by zero.");

        if (_numerator % _denominator !=0) {
            revert("Numerator must be divisable by Denominator");
        }

        return _numerator/ _denominator;

    }

'''
This is the whole functionality within the code itself and the generalization of how the code will run. 

## Running the Code
4th thing you'll need to do is deploy and run tab which is located below at the solidity compiler button. with it opening, you'll see the orange button that says deploy which grants you to see if your token is available or not. You'll have to test the waters a.k.a the tokens(abbrv, name, and total supply buttons) within the 'deployed contracts')

You'll need to set your values more than once to assess if the code is working, the requirements being -1 and 10 or more numbers

The divisible requires the numerator to be at least lower than denominator, that will determine if the code is working functionally.

  ### Advice
   Any advice can ask @ the discord with faith/Chris as my guide!

   ### Authors
   Rafanan, Jay-Ann
   @sakiwaree on discord
