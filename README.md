# observatoire-landing

## Notes
- It looks like there's a [conflict]((https://github.com/middleman/middleman-sprockets/issues/132)) between `middleman-sprockets` and `saasc`. The problem looks inextricable or it requires investigating at leats a day. As we'll drop this website to move it under the new woo website, we'll stay with this deprecated config.
- There's also a bundler version conflict. So run the `bundle` command with `_1.16.2_` option. For instance: `bundle _1.16.2_ install`. (Install `bundler 1.16.2` with `gem install bundler -v 1.16.2` if required)
