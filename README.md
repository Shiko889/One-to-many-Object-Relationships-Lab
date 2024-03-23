Introduction
This lab involves implementing a one-to-many relationship between an Owner and their Pets.

Instructions
This is a test-driven lab. Run pipenv install to create your virtual environment and pipenv shell to enter the virtual environment. Then run pytest -x to run your tests. Use these instructions and pytest's error messages to complete your work in the lib/ folder.

Instructions:
Define an Owner class and pass into the constructor a name argument.
Define a Pet class and pass into the constructor its name, pet_type, and an optional owner.
Define a class variable PET_TYPES that contains valid pet types.
Validate that the pet_type provided during initialization is one of the valid types specified in PET_TYPES. If not, raise an exception.
Define a class variable all in the Pet class that stores all instances of the Pet class.
Implement the following methods in the Owner class:
pets(): Returns a list of the owner's pets.
add_pet(pet): Checks that the pet is of type Pet and adds the owner to the pet.
get_sorted_pets(): Returns a sorted list of the owner's pets by their names.
Ensure that Owner and Pet classes use isinstance to check types whenever instances are passed into methods. Raise an exception if these checks fail.
