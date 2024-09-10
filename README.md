# ocr4all-docker
### Clone repository
```
git clone https://github.com/OCR4all/ocr4all-docker
```
### Set environment variables
- Copy the `template.env` to a file named `.env` that should be placed in the same directory as the `docker-compose.yml` file
- Set all required environment variables to the desired values
### Run
Start your OCR4all instance with the following command while inside the cloned directory
- `docker-compose up`
> [!NOTE]  
> Starting up the whole stack might take some time so if you can't login through the frontend right away just wait a few seconds and try again when everything has fully booted up.
