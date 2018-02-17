# Indigenous
Prerequisites 
- Linux Machine
- 2 Anroid Phones or Emulators

# Installation
- Open Terminal
- Move into directory containing requirements.txt 
- Install the dependencies 
```sh
$ pip install -r requirements.txt
```
# Server
  - Open server.py using your favourite code editor
  - Change the variable `BASE_DIRECTORY_STORAGE` to the directory where you would like to store data.
  - Change the variable `HOST_IP` to the intranet ip where clients will send request.
  - Run server.py
  ```sh
  $ python server.py
  ```

Server will collect location data of all transporters whenever available via GPS, quantity of produce at every market on a daily basis, and daily profit margins incurred by individual farmers for the specific produce.
This data will then be used as described in the report pdf.
