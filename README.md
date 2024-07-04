# data-parser
A Python library for parsing and processing various data formats
from data_parser import DataParser

# Initialize the parser
parser = DataParser()

# Parse CSV
csv_data = parser.parse_csv("example_data.csv")
print("CSV Data:")
print(csv_data)

# Parse JSON
json_data = parser.parse_json("example_data.json")
print("\nJSON Data:")
print(json_data)

# Parse XML
xml_data = parser.parse_xml("example_data.xml")
print("\nXML Data:")
print(xml_data)

