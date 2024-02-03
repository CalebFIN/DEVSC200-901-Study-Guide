# Parsing Common Data Formats to Python Data Structures
 
 Each of these formats can be parsed into Python's native data structures such as ```dictionaries``` and ```lists```

## [JSON](JSON.md)

### Example:
```python
import json

# Imagine you've got JSON data for a developer's daily routine
json_data = '{"wakeUpTime": "12:00 AM", "firstTask": "Check Emails", "lunchBreak": "4:00 AM", "afternoonTask": "Write Code", "coffeeIntake": ["Morning", "Pre-lunch", "Post-lunch", "Afternoon", "Bed-Time" , "Emergency"]}'
parsed_data = json.loads(json_data)

print(parsed_data)
```
```Shell
 Python> {'wakeUpTime': '12:00 AM', 'firstTask': 'Check Emails', 'lunchBreak': '4:00 AM', 'afternoonTask': 'Write Code', 'coffeeIntake': ['Morning', 'Pre-lunch', 'Post-lunch', 'Afternoon', 'Bed-Time', 'Emergency']} 
 ```

## [YAML](YAML.md)

```shell
pip install pyyaml
```
The `PyYAML` library, which **must** be installed, is used to parse YAML into Python data structures.

### Example:
```python
import yaml

# YAML data for a developer's gadgets
yaml_data = """
laptop: 80386 386 Dx 40MHZ
monitors: 1 
favoriteSnack: coffee Beans
keyboard: 4800-52 mainframe
mouse: TABKEY
"""

parsed_data = yaml.safe_load(yaml_data)

print(parsed_data)
```
```shell
 Python> {'laptop': '80386 386 Dx 40MHZ', 'monitors': 1, 'favoriteSnack': 'coffee Beans', 'keyboard': '4800-52 mainframe', 'mouse': 'TABKEY'}
 ```

## [XML](XML.md)

Python's `xml.etree.ElementTree` module can parse XML data.

### Example:
```python
import xml.etree.ElementTree as ET

xml_data = """
<playlist>
    <song>Code Monkey</song>
    <song>Debugging Blues</song>
    <beverage>Coffee</beverage>
</playlist>
"""

root = ET.fromstring(xml_data)

# Parsing XML data to a dictionary might require a bit more work
playlist = {"songs": [], "beverage": root.find("beverage").text}
for song in root.findall("song"):
    playlist["songs"].append(song.text)

print(playlist)
```
```shell
 Python> {'songs': ['Code Monkey', 'Debugging Blues'], 'beverage': 'Coffee'}
```