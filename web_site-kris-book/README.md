# Logger website
A simple representation of the softwares that allows the user to record with the BabyLogger, copying the files on the local computer and treat the files by using the appropriate softwares.

## How to deploy the web site
### Actual version
- Go to [here](https://docs.babycloudlab.com/) for the actual version of the website.
- On the server the main folder for deployment is in the following [Path] : `/var/www/html/babylogger`.

### Deploy the web site on localhost
- On the folder `/logger_web_site`, run:
- **`hugo`**: for the compilation.
- **`hugo server`**: to run the web site locally.
- on the browser, tape `http://localhost:1313/` to see the website up on your local machine.

### Deploy the web site on Remote Server/Cloud
  - After running the command befor, copy the folder `/public` on the server be careful of the source path on `config.toml`.
  
### Web site architect
- archetypes
- content
    - what is the BbayLogger?
        - how to use the babylogger?
        - overview
    - getting start
        - decrypt process
        - time synchronisation
        - SD card
        - Env install
    - automatic data treatment
        - post process
        - send to cloud
        - ML
    - faq
    - contact
- data
- layout
- public
- resources
- static
- themes
- config.toml
- README.md

### Sources
- https://gohugo.io/documentation/
  
| Version | Licence |
| ------ | ------ |
| V1.0 of 2019 | Echolalia |

