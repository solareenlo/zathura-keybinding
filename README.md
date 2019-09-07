# zathuraのキーバインド

## General

|キー|説明|
|:---|:---|
|J, PgDn|次のページへ移動する|
|K, PgUp|前のページへ移動する|
|h, k, j, l|左，下，上，右へ移動する（1カーソル分）|
|Left, Down, Up, Right|左，下，上，右へ移動する（1カーソル分）|
|^t, ^d, ^u, ^y|左，下，上，右へ移動する（半ページ分）|
|t, ^f, ^b, space, <S-space>, y|左，下，上，右へ移動する（1ページ分）|
|gg, G, nG|全体の最初，最後，nページに移動する|
|H, L|現在のページの最初，最後に移動する|
|^o, ^i|ジャンプリストを前後する|
|||

  ^j, ^k
    Bisect forward and backward between the last two jump points
  ^c, Escape
    Abort
  a, s
    Adjust window in best-fit or width mode
  /, ?
    Search for text
  n, N
    Search for the next or previous result
  o, O
    Open document
  f
    Follow links
  F
    Display link target
  \:
    Enter command
  r
    Rotate by 90 degrees
  ^r
    Recolor (grayscale and invert colors)
  R
    Reload document
  Tab
    Show index and switch to **Index mode**
  d
    Toggle dual page view
  F5
    Switch to presentation mode
  F11
    Switch to fullscreen mode
  ^m
    Toggle inputbar
  ^n
    Toggle statusbar
  +, -, =
    Zoom in, out or to the original size
  zI, zO, z0
    Zoom in, out or to the original size
  n=
    Zoom to size n
  mX
    Set a quickmark to a letter or number X
  'X
    Goto quickmark saved at letter or number X
  q
    Quit


## Fullscreen mode

  J, K
    Go to the next or previous page
  space, <S-space>, <BackSpace>
    Scroll a full page down or up
  gg, G, nG
    Goto to the first, the last or to the nth page
  ^c, Escape
    Abort
  F11
    Switch to normal mode
  +, -, =
    Zoom in, out or to the original size
  zI, zO, z0
    Zoom in, out or to the original size
  n=
    Zoom to size n
  q
    Quit

## Presentation mode

  space, <S-space>, <BackSpace>
    Scroll a full page down or up
  ^c, Escape
    Abort
  F5
    Switch to normal mode
  q
    Quit

## Index mode

  k, j
    Move to upper or lower entry
  l
    Expand entry
  L
    Expand all entries
  h
    Collapse entry
  H
    Collapse all entries
  space, Return
    Select and open entry


## Mouse bindings

  Scroll
    Scroll up or down
  ^Scroll
    Zoom in or out
  Hold Button2
    Pan the document
  Button1
    Follow link
