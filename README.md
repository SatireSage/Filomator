# Automated File Management System (AFMS)

Authors:
[Sahaj Singh](https://github.com/SatireSage), [Kaitlynn Chan](https://github.com/kaitlynnchan), [megarage9000](https://github.com/megarage9000)

Automated File Management System (AFMS) is a powerful and customizable tool for managing and organizing files on your computer. The project combines Python for backend operations and Electron.js for a sleek and user-friendly graphical user interface (GUI).

## HOW TO RUN

Follow these steps to set up and run AFMS on your local machine:

1. Install npm and node.js on your system
2. Navigate to the ui folder in the command line
3. Run `npm install` in the command line to get the node packages
4. Run `npm start` to load and open the electron window.
5. Enter all the information. The selected days of the week will be shown in yellow. The Source and Destination folders
   can be chosen by clicking the square button to the right which opens the file explorer. Click on the dropdowns for
   start time to select the hour and minute, and select whether the time is in AM or PM. Keywords and Extensions can be
   chosen by typing in the input sections and clicking the `Enter` key, they will then show up below in green. You can
   remove any keywords or extensions simply by clicking on them.

   ![new task page](./assets/new-task-page.jpg)

6. Once the task has been successfully added, navigate to the ../model folder in the command line.
7. Run `python main.py` in the command line. The program will now automate file management.

AFMS is now set up and will manage your files based on the configurations you provided.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
