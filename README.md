Bulk Letter Generation Script

This Python script is designed to generate personalized letters for a list of invited individuals, using a starting letter template and a list of names provided in separate text files.
Prerequisites

  Python 3.x installed on your system.
  Text files containing the list of names (invited_names.txt) and the starting letter template (starting_letter.txt) in the specified directory structure.

How to Use

  Ensure that you have the required input files (invited_names.txt and starting_letter.txt) in the appropriate directories (./Input/Names/ and ./Input/Letters/ respectively).
  Run the script.
  The script will read the list of names from invited_names.txt and the content of the starting letter from starting_letter.txt.
  It will then generate personalized letters for each individual, replacing the placeholder [name] in the starting letter template with the respective names from the list.
  The personalized letters will be saved in the ./Output/ReadyToSend/ directory with filenames formatted as letter_for_[name].txt.

File Structure

  Input
      Names
          invited_names.txt: Contains the list of names of invited individuals, with each name on a separate line.
      Letters
          starting_letter.txt: Contains the template of the starting letter, with the placeholder [name] to be replaced with individual names.

  Output
      ReadyToSend
          letter_for_[name].txt: Personalized letters for each invited individual, with [name] replaced by the respective name.

Usage Notes

  Ensure that the placeholder [name] in the starting letter template matches the format used in the list of names (invited_names.txt).
  Make sure the script has permission to read from and write to the specified directories.
