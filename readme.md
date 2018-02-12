# BadKarma

A userstyle to hide all karma on reddit.com.

## Why hide karma?

Hiding karma removes the gamification from Reddit.  It allows you to post without worrying quite so much about sharing the "wrong opinion", or being influenced in your own voting.

## Compatibility

|                                            | Chrome              | Firefox                 | Opera                   | Safari               |
|--------------------------------------------|---------------------|-------------------------|-------------------------|----------------------|
| [Stylus][stylus-home]<sup>1</sup>         | [Yes][stylus-ch]     | [Yes][stylus-fx]        | [Yes][stylus-op]        | No                   |
| [Stylish][stylish-home]                   | No<sup>2</sup>       | [Yes][stylish-fx]       | No                      | No                   |
| [FreeStyler][freestyler-home]<sup>1</sup> | [Yes][freestyler-ch] | [Yes][freestyler-multi] | [Yes][freestyler-multi] | [Yes][freestyler-op] |

[stylus-home]: https://add0n.com/stylus.html
[stylus-ch]: https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?hl=en
[stylus-fx]: https://addons.mozilla.org/en-US/firefox/addon/styl-us/
[stylus-op]: https://addons.opera.com/en/extensions/details/stylus/

[stylish-home]: https://github.com/stylish-userstyles/stylish
[stylish-fx]: https://addons.mozilla.org/en-US/firefox/addon/stylish/

[freestyler-home]: http://freestyler.ws/
[freestyler-ch]: https://chrome.google.com/webstore/detail/freestyler/hihigldmabkodfpehkgdemjklmaebmca?hl=en
[freestyler-op]: https://addons.opera.com/en/extensions/details/freestyler/?display=en
[freestyler-multi]: https://freestyler.ws/plugin-page

<sup>1. Stylus and FreeStyler can auto-install the userstyle by viewing the [raw file](https://raw.githubusercontent.com/WesCook/BadKarma/master/badkarma.user.css) and installing at the prompt.</sup>  
<sup>2. Currently this script does not work with Stylish on Chrome without removing the `@-moz-document` rule.</sup>

## Notes

* Subreddits that you moderate will be exempt from karma hiding.
