
# Read Me

Linkedin Crawling is Crawler that aims data from Linkedin to xlsx, this scraper works in about 1 - 5 sec / page depends on the internet .

## Run Locally

Clone the project

```bash
  git clone 
```

Install dependencies

```bash
  pip install requests
  pip install tenacity
  pip install pandas
  pip install timeit
```

Start the scraper

```bash
  python -m linkedin_crawler [start_page] [end_page]
```
Example :

```bash
  python -m linkedin_crawler 1 36
```
## Crawler Flow

![image](https://user-images.githubusercontent.com/39428898/208601319-f509fb03-83f5-404c-9051-6ece2a8afa28.png)


## Limitation

This crawler is only example how to crawl data from Linkedin. This method work's very efficient.

## Authors

- [Haydar Miezanie](https://github.com/haydarmiezanie)
