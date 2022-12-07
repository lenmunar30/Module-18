# Module-18: PyChain

![image](https://user-images.githubusercontent.com/108433370/206277673-d9879d43-4905-4e92-b882-5f9927dba066.png)

## BACKGROUND

For this challenge we are working as a fintech engineer at one of the largest banks in the world. We are tasked with building a blockchain-based ledger system, complete with a user-friendly web interface.

In this challenge we will create a record data class, modify the already existing block data class to store the record data, add functional user input availability to the streamlit interface, and test the ledger by successfully storing records.

=======================================================================================================

## TECHNOLOGIES

This project leverages python 3.7 with the following packages:

datetime - This module supplies classes for manipulating dates and times.

streamlit - This program allows for the creation of web apps from python code.

Pandas - Pandas is a powerfull tool for data analysis and manipulation. Pandas provides a plethora of useful functions that make it easy to express, analyze, and manipulate data.

hashlib -This module implements a common interface to many different secure hash and message digest algorithms.

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

======================================================================================================

## Process

Create a Record Data Class

Modify the Existing Block Data Class to Store Record Data

Add Relevant User Inputs to the Streamlit Interface

Test the PyChain Ledger by Storing Records

### Step 1: Create a Record Data Class

Define a new class named Record.

Add the @dataclass decorator immediately before the Record class definition.

Add an attribute named sender of type str.

Add an attribute named receiver of type str.

Add an attribute named amount of type float.

### Step 2: Modify the Existing Block Data Class to Store Record Data

In the Block class, rename the data attribute to record.

Set the data type of the record attribute to Record.

### Step 3: Add Relevant User Inputs to the Streamlit Interface

Delete the input_data variable from the Streamlit interface.

Add an input area where you can get a value for sender from the user.

Add an input area where you can get a value for receiver from the user.

Add an input area where you can get a value for amount from the user.

As part of the “Add Block” button functionality, update new_block so that Block consists of an attribute named record, which is set equal to a Record that contains the sender, receiver, and amount values. The updated Block should also include the attributes for creator_id and prev_hash.

### Step 4: Test the PyChain Ledger by Storing Records

Test your complete PyChain ledger and user interface by running your Streamlit application and storing some mined blocks in your PyChain ledger. Then test the blockchain validation process by using your PyChain ledger.

==============================================================================================================

## OUTPUT

![image](https://user-images.githubusercontent.com/108433370/206283865-1857e167-e080-4fc4-9199-2bf0d0b12063.png)

![image](https://user-images.githubusercontent.com/108433370/206283917-5c4c1db6-b852-4562-b0ab-11ffdca24c3e.png)




##



