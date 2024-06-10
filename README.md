"""
This program calculates prices for custom house signs.
"""

# Declare and initialize variables here.
charge = 0.00
num_characters = 18
color = "black"
wood_type = "oak"

minimum_charge = 35.00
additional_character_charge = 4.00
oak_charge = 20.00
gold_leaf_charge = 15.00

# Charge for this sign.
# Number of characters.
# Color of characters.
# Type of wood.

# Write assignment and if statements here as appropriate.
charge = minimum_charge
if num_characters > 5:
    charge += (num_characters - 5) * additional_character_charge
if wood_type == "oak":
    charge += oak_charge
if color == "gold":
    charge += gold_leaf_charge
      

# Output Charge for this sign.
print("The charge for this sign is $" + str(charge))
