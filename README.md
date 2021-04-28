## Adding images

1. Go to issues and select any issue
2. Drag and drop your image into the comment box
3. After it uploads, copy the text (should look something like this: 
`![IMG_7191 copy](https://user-images.githubusercontent.com/18628685/116429899-f137ba80-a80b-11eb-91bb-be95262596f6.JPG)`)
4. Paste the text from #3 into the post where you want the image

## Development

Poole has two branches, but only one is used for active development.

- `master` for development. **All pull requests should be to submitted against `master`.**
- `gh-pages` for hosted demo **Please avoid using this branch.**

CSS is handled via Jeykll's built-in Sass compiler. Source Sass files are located in `_sass/`, included into `styles.scss`, and compile to `styles.css`.

### Customize Navbar

You can easily customize the navbar by tweaking the `_config.yml` file. Simply change the title and url of each of the nav elements, or add more. The order will be preserved in the site.

```yaml
nav:
  - title: Blog
    url: /archive

  - title: About
    url: /about
```

## Author

**Mark Otto**

- <https://github.com/mdo>
- <https://twitter.com/mdo>

## License

Open sourced under the [MIT license](LICENSE.md).

<3
