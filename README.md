<center>
  <h1>HBNB - The Console</h1>
</center>

This repository contains the second version of the HBNB project, which aims to create a clone of the AirBnB website. In this version, we have developed a backend console interface to manage various objects and data related to property rentals. The console allows users to interact with the system, create, update, and delete objects, and persist data using JSON serialization/deserialization.

---

<center>
  <h3>Repository Contents by Project Task</h3>
</center>

| Task | Files | Description |
| --- | --- | --- |
| Task 0: Fork and Update Repository | [README.md](./README.md) | Initial repository setup with updated information |
| Task 1: Pep8 | N/A | All code is pep8 compliant |
| Task 2: Unit Testing | [/tests](https://github.com/yourusername/AirBnB_clone_v2/tree/main/tests) | Unit tests for class-defining modules |
| Task 3: Make BaseModel | [/models/base_model.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/base_model.py) | Define a parent class for all model classes |
| Task 4: Update BaseModel w/ kwargs | [/models/base_model.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/base_model.py) | Add functionality to recreate an instance from a dictionary |
| Task 5: Create FileStorage class | [/models/engine/file_storage.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/engine/file_storage.py) [/models/__init__.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/__init__.py) [/models/base_model.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/base_model.py) | Define a class for persistent file storage |
| Task 6: Console 0.0.1 | [console.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/console.py) | Basic console functionality with quit, empty line handling, and ^D |
| Task 7: Console 0.1 | [console.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/console.py) | Update console with create, destroy, show, and update commands |
| Task 8: Create User class | [console.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/console.py) [/models/engine/file_storage.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/engine/file_storage.py) [/models/user.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/user.py) | Dynamically implement the User class |
| Task 9: More Classes | [/models/user.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/user.py) [/models/place.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/place.py) [/models/city.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/city.py) [/models/amenity.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/amenity.py) [/models/state.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/state.py) [/models/review.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/review.py) | Dynamically implement more classes |
| Task 10: Console 1.0 | [console.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/console.py) [/models/engine/file_storage.py](https://github.com/yourusername/AirBnB_clone_v2/blob/main/models/engine/file_storage.py) | Update the console and file storage system to work dynamically with all classes; update file storage |

<br>

<center>
  <h2>General Use</h2>
</center>

1. **Clone this Repository:**

git clone https://github.com/yourusername/AirBnB_clone_v2.git


2. **Run the Console:**

Navigate to the project directory and run the console:

cd AirBnB_clone_v2
./console.py


3. **Using the Console:**

The console prompt `(hbnb)` will appear. You can use various commands to interact with the system:

- `create`: Create an instance of a class.
- `destroy`: Delete an object by class and ID.
- `show`: Show an object by class and ID.
- `all`: Show all objects or all objects of a specific class.
- `update`: Update object attributes by class, ID, and key-value pairs.
- `quit`: Exit the console.

4. **Alternative Syntax:**

Some commands support alternative syntax, such as `Class.command()`.

---

<center>
<h2>Authors</h2>
</center>

- **Author 1:**
- Name: Ayoub Eladib
- Email: ayoubeladib906@gmail.com

- **Author 2:**
- Name: Muhaymin Olalekan
- Email: muhayminolalekan@yahoo.com

---

Replace the placeholders (e.g., "Task 1: ...") with the descriptions of each task you provided earlier. This README.md file is structured to provide a clear overview of your project's tasks, their descriptions, and how to use the project. You can further customize it as needed for your specific project requirements.

