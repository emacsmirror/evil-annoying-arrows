# evil-annoying-arrows-mode

Entering evil-annoying-arrows-mode makes evil-emacs ring the bell in your face if you move
long distances in the buffer one char at a time.

    ;; Evil annoying arrows mode
    (require 'evil-annoying-arrows-mode)
    (global-evil-annoying-arrows-mode)

Set the `evil-annoying-arrows-too-far-count' to adjust the length.

## Original author

* [Magnar Sveen](https://github.com/magnars)

## Contributors

* [Piers Cawley](https://github.com/pdcawley) added `aa-add-suggestion` for easier extension

Thanks!
