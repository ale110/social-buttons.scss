# Wonderful Buttons

## Usage
* Drop `_social-buttons.scss` and `_variables.scss` files into your project
* Include a mixin:
    ```scss
    .btn, button {
      @include social-button(color border);

      &:hover {
        @include social-button(background-color);
        color: white;
      }
    }
    ```

## License
MIT

### Contributing
You can request new button as issue or pull request [in this repo](https://github.com/theaqua/social-buttons.scss/issues) and I'll eventually pull it here.
