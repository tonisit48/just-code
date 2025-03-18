import requests


url = 'https://wttr.in/svo&lang=ru'
response = requests.get(url)
response.raise_for_status()
print(response.text)

import requests


url = 'https://wttr.in/london&lang=en'
response = requests.get(url)
response.raise_for_status()
print(response.text)

import requests


url = 'https://wttr.in/Cherepovets?MnqT&lang=ru'
response = requests.get(url)
response.raise_for_status()
print(response.text)
