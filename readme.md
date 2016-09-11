# tachyons-border-colors 4.1.3

Performance based css module.

#### Stats

605 | 58 | 58
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-border-colors
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-border-colors
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-border-colors.git
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-border-colors";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the CSS

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-border-colors@4.1.3/css/tachyons-border-colors.min.css" />
```

##### Locally
The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-border-colors">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   Tachyons
   COLOR VARIABLES

   Grayscale
   - Solids
   - Transparencies
*/
/*

   BORDER COLORS

*/
.b--black { border-color: #000; }
.b--near-black { border-color: #111; }
.b--dark-gray { border-color: #333; }
.b--mid-gray { border-color: #555; }
.b--gray { border-color: #777; }
.b--silver { border-color: #999; }
.b--light-silver { border-color: #aaa; }
.b--light-gray { border-color: #eee; }
.b--near-white { border-color: #f4f4f4; }
.b--white { border-color: #fff; }
.b--white-90 { border-color: rgba( 255, 255, 255, .9 ); }
.b--white-80 { border-color: rgba( 255, 255, 255, .8 ); }
.b--white-70 { border-color: rgba( 255, 255, 255, .7 ); }
.b--white-60 { border-color: rgba( 255, 255, 255, .6 ); }
.b--white-50 { border-color: rgba( 255, 255, 255, .5 ); }
.b--white-40 { border-color: rgba( 255, 255, 255, .4 ); }
.b--white-30 { border-color: rgba( 255, 255, 255, .3 ); }
.b--white-20 { border-color: rgba( 255, 255, 255, .2 ); }
.b--white-10 { border-color: rgba( 255, 255, 255, .1 ); }
.b--white-05 { border-color: rgba( 255, 255, 255, .05 ); }
.b--white-025 { border-color: rgba( 255, 255, 255, .025 ); }
.b--white-0125 { border-color: rgba( 255, 255, 255, .0125 ); }
.b--black-90 { border-color: rgba( 0, 0, 0, .9 ); }
.b--black-80 { border-color: rgba( 0, 0, 0, .8 ); }
.b--black-70 { border-color: rgba( 0, 0, 0, .7 ); }
.b--black-60 { border-color: rgba( 0, 0, 0, .6 ); }
.b--black-50 { border-color: rgba( 0, 0, 0, .5 ); }
.b--black-40 { border-color: rgba( 0, 0, 0, .4 ); }
.b--black-30 { border-color: rgba( 0, 0, 0, .3 ); }
.b--black-20 { border-color: rgba( 0, 0, 0, .2 ); }
.b--black-10 { border-color: rgba( 0, 0, 0, .1 ); }
.b--black-05 { border-color: rgba( 0, 0, 0, .05 ); }
.b--black-025 { border-color: rgba( 0, 0, 0, .025 ); }
.b--black-0125 { border-color: rgba( 0, 0, 0, .0125 ); }
.b--dark-red { border-color: #f00008; }
.b--red { border-color: #ff3223; }
.b--orange { border-color: #f3a801; }
.b--gold { border-color: #f2c800; }
.b--yellow { border-color: #ffde37; }
.b--purple { border-color: #7d5da9; }
.b--light-purple { border-color: #8d4f92; }
.b--hot-pink { border-color: #d62288; }
.b--dark-pink { border-color: #c64774; }
.b--pink { border-color: #f49cc8; }
.b--dark-green { border-color: #006C71; }
.b--green { border-color: #41D69F; }
.b--navy { border-color: #001b44; }
.b--dark-blue { border-color: #00449e; }
.b--blue { border-color: #357edd; }
.b--light-blue { border-color: #96ccff; }
.b--lightest-blue { border-color: #cdecff; }
.b--washed-blue { border-color: #f6fffe; }
.b--washed-green { border-color: #e8fdf5; }
.b--washed-yellow { border-color: #fff8d5; }
.b--light-pink { border-color: #efa4b8; }
.b--light-yellow { border-color: #f3dd70; }
.b--light-red { border-color: #ffd3c0; }
.b--transparent { border-color: transparent; }
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

