# AirBnB_clone - Console


# Description of the project
The first part of this project involves simulating an Airbnb application by creating a control system for the modules used on our web page. We achieve this by implementing a JSON-format database and leveraging object-oriented programming, Python data translation, and command interpretation. The result is a local database that can be easily modified using specific commands, providing a flexible and efficient way to manage data.

# Installation
```
git clone https://github.com/MisheckGalx/AirBnB_clone.git  
cd AirBnB_clone
```

# Run
```
./console.py or python3 console.py
```

# Testing
```
python3 -m unittest discover tests
```

# Prerequisites
```
sudo apt-get install python3
```

### Commands Explanation:
**create** - Creates a new instance of BaseModel, saves it (to the JSON file) and prints the id.  
**Example**:  
```
$ create BaseModel
```

**show** - Prints the string representation of an instance based on the class name and id.  
**Example**:  
```
$ show BaseModel 1234-1234-1234
$ BaseModel.show("<id>")
```
    
**all** - Prints all string representation of all instances based or not on the class name.  
**Example**:  
```
$ all BaseModel
$ all
$ BaseModel.all()
```
        
**update** - Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file).  
**Example**:  
```
$ update BaseModel 1234-1234-1234 email "airbnb@alxafrica.com"`
$ BaseModel.update("<id>", "<attribute>", "<value>")`
$ BaseModel.update("<id>", {"field1":"value1", "field2":int_value})
```

# AUTHORS
**[Misheck Gogo](https://github.com/MisheckGalx)**  
**[Brian Musakwa](https://github.com/digreatbrian)**
