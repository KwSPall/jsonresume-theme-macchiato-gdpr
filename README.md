# Macchiato+GDPR Theme!

Macchiato+GDPR it's a [JSON Resume](https://jsonresume.org/) theme based on [Macchiato](https://github.com/biosan/jsonresume-theme-macchiato).

## Why?

I needed to add gdpr consent statement to the resume and I liked the original theme.

> ***Currently it doesn't have any style difference from it's parent [Macchiato](https://github.com/biosan/jsonresume-theme-macchiato).***


## Changes from Macchiato Theme

### Visual differences

- Use `meta.gdpr.company` and `meta.gdpr.extended` to generate consent statement required in some countries.

```
{
  (...)
  "meta": {
    "gdpr": {
       "company": "Test Company",
       "extended": "true"
    }
    (...)
  }
  (...)
}
```


## Usage

1. Download [JSON Resume CLI](https://jsonresume.org/)
  ```
  npm install -g resume-cli
  ```

2. Clone this repository and cd into it

3. Run resume-cli with this theme
  ```
  resume serve --theme=.
  ```

4. Use resume cli to build your resume
  ```
  resume export resume.html --theme=.
  ```

## License

Available under the [MIT license](http://mths.be/mit).

