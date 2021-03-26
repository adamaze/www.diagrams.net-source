---
title: List of diagrams.net plugins
layout: page
faq: true
categories: [Plugins]
---

_Plugins should be used as-is, as unsupported examples for developers._

There are a number of built-in plugins that can be added to diagrams.net, either added as a one-off or loaded every time you use diagrams.net with that browser.

To load a plugin, use the ``p=xxxx`` URL parameter, separating multiple plugin IDs with a semicolon. This does not permanently load the plugin, so the next time you create a diagram it won't be available.

For example:
* To load the anonymize plugin: [https://app.diagrams.net/?splash=0&p=anon](https://app.diagrams.net/?splash=0&p=anon)
* To load both the anonymize and text plugins: [https://app.diagrams.net/?p=anon;text](https://app.diagrams.net/?p=anon;text)

To [permanently add plugins](/doc/faq/add-plugin.html), select a plugin from the list of built-in plugins via the _Add Plugin_ dialog, click _OK_ and then _Apply_ to save your changes. Make sure you reload diagrams.net in your browser tab after you permanently add or remove a plugin.

<img src="/assets/img/blog/add-explore-plugin.png" style="width=100%;max-width:200px;height:auto;" alt="Add the explore plugin">

**Note:** Plugins are not part of the core functionality of diagrams.net, they are intended as examples for developers to create additional functionality.

The following plugins are available from the [diagrams.net Github repository](https://github.com/jgraph/drawio/tree/master/src/main/webapp/plugins).

| **Filename** | **ID** | **Description** |
|--------|----------|----------|
| _example plugin_ | [p1](https://app.diagrams.net/?splash=0&p=p1) | Defines a custom sidebar and placeholders ([source code](https://app.diagrams.net/plugins/p1.js)) |
| explore.js | [ex](https://app.diagrams.net/?splash=0&p=ex) | Adds _Explore from Here_ to the context menu, and a click handler to the lightbox ([example](https://app.diagrams.net/?chrome=0&p=ex&lightbox=1&edit=_blank&layers=1&title=Department%20Activity#R7Vxbc6M4Fv4t%2B5BHu9BdPCbpzvbDbM1U9UztMwbZZhojL%2BB0sr9%2BhQEbSdhYAZKs3U5VNwhdQOec71zhDj1uXv6ZBdv1v2QkkjvoRS936MsdhBwB9W%2FZ8Fo3AFo1rLI4qpq8Y8P3%2BL%2BiagRN6y6ORF63VU2FlEkRb%2FXGUKapCAttxiDL5M9ca1rKJNLGbYOVsBq%2Bh0Fit%2F47jop1%2FRTEO7Z%2FE%2FFqXa8MgFdfWQThj1Umd2m93h1Ey%2F2vurwJmrnq%2Fvk6iOTPVhP6eoceMymL6mjz8iiScmv1bXs6cfVw35lIi0sGwGrAc5Ds6kcPMxEUau%2Br2ytemy0Rkdqh%2BjSVqfrvIdxlz6KcCJQnchOH6thTx3%2BLonitqRrsCqmaZFas5UqmQfKblNt6TF5k8sdhh9XDPyxlWtQDAVLnqfzaWhdoE9UN1Z2Wt6ftQS53WVg3oZqFgmwl6m0h9k6Bw%2F4rthZyI4rsVXWpeVpRvxry2rAqmfvUgz72ke95xKsvBzXrrQ4z1JPeZ1nw2uqwlXFa5K01%2Fygbjgsin89R%2B8f09SHXKWsMt%2B63Pq%2F7q4Pqhpqz1jMfm%2Fbc0s05yOKcL0LtZrER%2B7u4D4v4OS7UAyvJRy%2BBItSsdfyYxOEP1e2byMQ%2FbF5LEiXp4iIOWcZJ8igTme2HoiUp%2Fw4jW1fo%2FtfMcOCo6ilEVoiXkzJ0njMQ1Xca1lj384gcgNfyvm6hhu%2Bd5pgWmc5SAdvyq54uiNPrEmBiCzB1JROAOpnoyPIKMZjT9s%2FXucI%2FL6%2BA6LeHEHXqj%2F1p%2B1Nyvj%2FkOj5RDk%2FjjTV6Bjx9uxoLotl9uVzmivSmaLhhFrExS4a7ErFsccnWcrPY5TVLPwWbOClv7ZtInkURh0EXFKnzFuB4%2B59qD5J4laq2UC0ksi5siuii3N9OgTLwbbmEYXiQmkHApWissyjoQC7cgVxsBOSiJ2mhWoFFDmUobcvDqOn0WelSUkTdRnJfT16UYPmQb4MwTld%2F7pHTH4l8DRleG6rY5OvSO3QE6rGb1Tt8ar1jYSNDeE4YUYzLAfMhATpQEn%2BOGedY9fOhD4zpq6epZzzS11m5GdYk8gy%2FwtQeZv8%2BbcYdtdPA%2Fn3aDHA4N0b42EWfGVSaQUPoRtFn%2FByGwl8YeoFw0o%2FDUP9mMRR4znQaDKKYzD1O1e0QyDjwkA5PjJZXkUJQRglmDE2Cogieden7XATTXusDVbN%2FH0gO7d8HqtjYdVcXgeiyOkP%2BBJja8GY3qKJfoNovrIh%2FHKgCYJEvTp%2BlosF1oWpHSBMgV0Jhw8cHpvXYj6u%2Bx%2BYMMYWsDHoeMiYkvsJV6HFIGVZ8YIRIR0JV6ynQedvU7A%2B9M5bdWxAE3oZiB1086E%2Bt2Z25A%2BhhOTeViwz7sE%2FlIgLdVKgBlaTe6MtUItRjZjM2iUK0I%2F1%2FCLlVrGMy87uGzGjIxWJ5iQaMAsGXI4XMEP%2FAkBm4kWh%2FF7BAODWw2DEAzzsXeMHoLYEXW4FyOofddv1hrmojhitKI6PYbMmFWEiIGxaa%2FfuwkCADC5FLxAUaARc6CRbaGYTbkUDmKoGWocXfIIPgnN%2BOyZv89o5lCJgTxDEF1b9YXwZPJJBmzq8nqmr1ZyNbrnZSRnHjWilS6MnldXG4b3P45KF956i7keGhoC9AxAZFrU0MRVMErYGdO7olJnOuW0DAYAJvbDazVjCLxvr6%2B3BcGLLzGokMg0LRXD1UcfUsgpyByNelftZEwcZjEeKGRGQgEs2MmqpZEyofAkV%2F5SL7ffF3WTAKvSRYiKSa6w6SNNgof1atSZMygrtQYERXxZ6EVUussRz9z66s0FSctfcy7%2B%2FKQtZyQ5sLx%2BFkK%2FO4iGXaml7dV2wuYC8ZlC5kJpbaipsgTkquVUsSUZ5U0xrLfq2uHFYLjnOXm7h%2F2tqTz%2FLy1pqKi8PN7q9%2B3y2KuGg8%2FWq5%2FQU1HHviJdhsEzFX4lUPToJQrGUSqUk1hj8Itt%2FisFroW3Jck%2BQh3lTlueuiKOt970sSw6cwStE8Vub2Mk7VCtWyT1FQBOV2qnbFvk87ReJZ8Kwas3ymVn8iZTRu35zP%2FJmSDMjn23SlVtlX6R4w4lTM4HTcYV1sdDkfVsyBjcgp7ggsoHGC5uq0JQrdGAztNMi1aukmtDAsQzk5BGNHYxCjYRDM9eeBU%2FjT0M7WXK2m72Iz5FyGPjmbmVGYPjajeKCmRyaj8V%2BafkpND99D01fM%2FmGa%2FvPqeYw%2BmZ63szv5biuy5zi%2FSl3PbBBugNmBiIYqtuKDoyt7THsig8whdv4WRW2nnm6NTdxT29ObhEYgBpOebDY2s80umrrZgGktQjvDcrV%2BRweTfbq3mrDBMlhPOXTU%2BLnVEJr9%2B2oIETJrCJkLCxu2JpkiwN3xasv1OjUdPIyc9en0To3nBpQUmuX%2FbsnoGTYYDRmJyV9OzbhOTVP6OK1Tw1oc9v5ODfq0Tg3yjcoQ%2FsFOjZ1AKoIfZQVwReTrw%2BGOeg3kHMIkZqmkXgXh%2FMUD%2ByUMQObAU4MhRwzyxvFqVDkjc8wJ4eUfw9iIA41ULdz3kD2fVaCGvQVGzn3eyltBDXcOMxymtn4JH1I8TIzi3t6COaN%2Fn%2B1MqW5lEKj177VRDKsLDzdR7K%2BE2Gmk30pbOJYd%2FPyu9cMcLhC96A2aiAge4XE0JTFL4t6zfhjZ2Zbyiy3X51k3QKKBy%2BcL31BDAvtSLcwswujxlc3%2B3Ovpb3hJHJ%2FRbR3v53Fzv0bI5NhMDC0m%2Fn25jPdG3enPRmwzGYo8v4gHLew4hQenMWUMpDDYj5AOpPA6kAKPgRR2VuB2rBDnnOzgNw18D8%2BZPgcDeM4nemFO2Q3aewC6Bdxn1TDHDxWZ%2FfusmqH9%2B1CR%2BsM%2B7WAQyqT2OCBnp1uuVFN3fB3AXVNT80s4ZGxHwFqB9biJRn9OxnUTkZ0mOWhBeEVasClFPsLie2pBO5B%2FO1rw%2Fb9zxLmuiFhtfo6u%2FszX7XreumEnXs%2B7tH%2BvAhvYv0%2FhETpM4YHGb2wMe9MsGUfl2a%2BFXKnK42OoPIKnVnnWCn0qDzt4j29hEDuof1B5pz%2FL8v%2Bn8rD%2FkSrPDj8%2F7OIkitPVlfnXpmXB6XTbrE6Pn%2FSuWP%2F42XT09X8%3D), [how to use](/doc/faq/explore-plugin.html)) |
| voice.js | [voice](https://app.diagrams.net/?splash=0&p=voice) | Adds a voice assistant via the _Voice_ menu ([how to use](/doc/faq/voice-plugin.html))|
| tooltips.js | [tips](https://app.diagrams.net/?p=tips&lightbox=1&edit=_blank#Uhttps%3A%2F%2Fjgraph.github.io%2Fdrawio-diagrams%2Fdiagrams%2Ftooltips.xml) | Adds an icon for shapes and connectors with tooltips ([example](https://app.diagrams.net/?p=tips#RzZTRToMwFIafhksTSje3a6dOlyzLnMZ4ZTo40ppCSekG7OltRwt0S9TdGG%2Bg%2FXranvP%2FBwI8y%2Bq5JAVdigR4EIVJHeDbIIoQmkT6ZUjTkulo1IJUssQG9WDDDmBhaOmOJVB6gUoIrljhw1jkOcTKY0RKUflhH4L7txYkhTOwiQk%2Fp68sUdRWMQ57%2FgAspe5mFNqVjLhgC0pKElENEL4L8EwKodpRVs%2BAG%2FGcLqunMVpM1mixPoyyasne35b7q%2Faw%2B0u2dCVIyNVvj34pQa62n0bSKORkq2097nzUU0r2YOTtvfCMaQOfKStNZuahKJzGfptx1MnTVViqxlkixS5PwOwPA3xTUaZgU5DYrFa6CTWjKjPpIj1sb9uDVFCfOPqDHGiQxBxEBko2ep89xbna%2BNOq7xHkGB30x7VlxLZl2h3cS68Htmw3HZhxge%2FY1k74Ds7My8WpI%2F9NYTT9S4n77%2FC4Nvib4bsv)) |
| svgdata.js | [svgdata](https://app.diagrams.net/?splash=0&p=svgdata) | Adds metadata and IDs in the SVG export |
| number.js | [number](https://app.diagrams.net/?lightbox=1&p=number#Uhttps%3A%2F%2Fjgraph.github.io%2Fdrawio-diagrams%2Fdiagrams%2Fbulb.xml) | Numbers all shapes in chromeless mode ([how to use](/doc/faq/number-plugin.html)) |
| sql.js | [sql](https://app.diagrams.net/?splash=0&p=sql) | Adds _Arrange > Insert > Advanced > From SQL_ ([how to use](/doc/faq/sql-plugin.html))|
| props.js | [props](https://app.diagrams.net/?lightbox=1&p=props&#Uhttps%3A%2F%2Fjgraph.github.io%2Fdrawio-diagrams%2Fdiagrams%2Fbulb.xml) | Shows shape metadata in chromeless mode ([example](https://app.diagrams.net/?lightbox=1&p=props&#Uhttps%3A%2F%2Fjgraph.github.io%2Fdrawio-diagrams%2Fdiagrams%2Fbulb.xml), [how to use](/doc/faq/properties-plugin.html)) |
| text.js | [text](https://app.diagrams.net/?splash=0&p=text) | Adds _Extras > Extract Text_ for extracting all of the text in a diagram |
| animation.js | [anim](https://app.diagrams.net/?lightbox=1&p=anim&edit=_blank#R7VrbkuI2EP0aHuPSxdfHHQZ2U5VUpmo2leRRgzVYO8aiZDFAvj6SLYOEMJeFmd2p4AcKteRuSX1Od0swwMPZ6rMg8%2BJ3ntNygEC%2BGuD7AUJJFKpPLVi3Aghj3EqmguVGthU8sn%2BpEQIjXbCc1s5AyXkp2dwVTnhV0Yl0ZEQIvnSHPfPStTonU%2BoJHiek9KV%2FsVwWrTRF8Vb%2BhbJpITfry9qeJzJ5mQq%2BqIy9AcLPzdN2z0inyyy0LkjOl5YIjwZ4KDiX7bc%2Fayr%2BePqm14hASZ7UPhu9zVIrpjQyXrXCulCqEAj1iklOB3q6WG0pvjM9sd%2BzJEyrjgDwh%2BPzhie9drPenrTXBAT7bEB48khwruo9u9N1Rf1dqL%2Brf%2F96ZpDskaX%2B27h5WxvuyLSFzmw1pKUi47htqi8WhJwRgO1yQtBK2ugc97xg2P1KygW14VjLdUegZcEkfZyTiW4vVZBQsy%2FkTKMXNoszsG9WKgV%2F2fAsVJJnVpZDXnLRKFOyERxHWs4raYKF8ha%2BIyWbauxP1MSpGnw3FSRnqmG9bOjXmel6Kl4pNXf%2B0s1uvFIh6coSma34TPmMSrFWQ0xvanyxdpvLbdwIO3cVVsyIEyMkJlZNN5qR7T6z%2B%2Fs9ER%2F3hHpBRU3abvpcCyclX%2BQaTdf00bh5jrjgqP%2FeykcQQsdJEPpewjDzvQSv4aXI89KYC2rSxJnc0zFi18O5yl2myYUs%2BJRXpBxtpXeNJZobX%2Fb5mFb5J507VfOp5JOXrwWrWvGYld0b36iUa%2BNDspBcibY2f%2BN83ml2AION88dkxkrtgy%2B0fKWSTcgOKtK9qDDAfS7pysxwP1J2MAlAHA%2BH7RK6mTS4U21jMApCpKlgerX5mi%2FEhD5QwZSjqdAEYdVUdf6C9sN7E558XxrPtyqNA00lJImYUjPM%2BFQ78hQ0Y4ADjFQO7p7IAXcYRkGErSfuh7Cx8cBZJS0DGDkaoxAHwHqQq9DsWKvDxu6O2hBgR20cJoE9z8hV2%2B6Qp1YhgKytYXM9oO5fTBi6ARpm6Q55W41bKm92%2FCR2w%2FTGyI%2FNSHQ5I%2BFhRkaXMjKMwA51skPUOZWROM6CFMEQpVGiP8PQsdLU529ASYjelpLYS7hfC6qzPdHwVcfG9USxcJe1qpaQO2Q8Bmkj8vihKxNFpfKT6ZixPG94v6%2Fm4mr0c9mwvFDjaLUbBiw6orRrm3nDQzzuhf8ZlVPkxmwI%2FMoJxXvq2%2FAKhVPi%2BXHIVdis6vbQi%2BJSO%2BxJuTSe6m8qOirn6vK29ry7jbjwotoXHTifHKt9jwVbFB4vipXO8D7LALDs3TOhjnftPcCS1vJKrs%2BSIDGBof10kRCDANkP9oABYxQA7GuwcZKEQWw%2F2eWwST3YPKj9YXMmDW5u0HhbaOA9x6sfhIXsYHFm4vetGrtaNZaTuthQ6aTyK%2FGrr%2FTE6kvQUjH61b20vQQtHW6t0PFrpXZNChM5hn7SEYuKd%2Fe77xRUolHa3MH8r4JKqPKNXfLi5GeJMd3l0i3IvFOQoSsm%2F9YbFkSm9c85ESf1I05H%2FFMPfCiBBw98OL3wwHehgVMPgChJg9SmjHsADBMQpNaTJa6ZnvPg99yiIP%2FMJkhVz5m4FW3Xia%2BZe6kXY%2Ff2Lfxpwql%2FfB%2B9kjm%2FAeFKQMAQBlm8cWqUfBBcRJ7vbxet75h1T8qtXSJ1kis6M7mmh29T0aW3qShzfw7E2femz0zlxzhT6RgkAMeom4qVPt%2F%2BBw61IY7VKEkOThom%2BND4y38QiW88%2FZg8xWfyNDvMU3wxT6MdZF%2Fnd0iY%2FojfITE6j6Y4uypNVXP7t7J2%2BPa%2Fe3j0Hw%3D%3D) | Adds _Extras > Animation_ which autostarts in chromeless mode ([example](https://app.diagrams.net/?lightbox=1&p=anim&edit=_blank#R7VrbkuI2EP0aHuPSxdfHHQZ2U5VUpmo2leRRgzVYO8aiZDFAvj6SLYOEMJeFmd2p4AcKteRuSX1Od0swwMPZ6rMg8%2BJ3ntNygEC%2BGuD7AUJJFKpPLVi3Aghj3EqmguVGthU8sn%2BpEQIjXbCc1s5AyXkp2dwVTnhV0Yl0ZEQIvnSHPfPStTonU%2BoJHiek9KV%2FsVwWrTRF8Vb%2BhbJpITfry9qeJzJ5mQq%2BqIy9AcLPzdN2z0inyyy0LkjOl5YIjwZ4KDiX7bc%2Fayr%2BePqm14hASZ7UPhu9zVIrpjQyXrXCulCqEAj1iklOB3q6WG0pvjM9sd%2BzJEyrjgDwh%2BPzhie9drPenrTXBAT7bEB48khwruo9u9N1Rf1dqL%2Brf%2F96ZpDskaX%2B27h5WxvuyLSFzmw1pKUi47htqi8WhJwRgO1yQtBK2ugc97xg2P1KygW14VjLdUegZcEkfZyTiW4vVZBQsy%2FkTKMXNoszsG9WKgV%2F2fAsVJJnVpZDXnLRKFOyERxHWs4raYKF8ha%2BIyWbauxP1MSpGnw3FSRnqmG9bOjXmel6Kl4pNXf%2B0s1uvFIh6coSma34TPmMSrFWQ0xvanyxdpvLbdwIO3cVVsyIEyMkJlZNN5qR7T6z%2B%2Fs9ER%2F3hHpBRU3abvpcCyclX%2BQaTdf00bh5jrjgqP%2FeykcQQsdJEPpewjDzvQSv4aXI89KYC2rSxJnc0zFi18O5yl2myYUs%2BJRXpBxtpXeNJZobX%2Fb5mFb5J507VfOp5JOXrwWrWvGYld0b36iUa%2BNDspBcibY2f%2BN83ml2AION88dkxkrtgy%2B0fKWSTcgOKtK9qDDAfS7pysxwP1J2MAlAHA%2BH7RK6mTS4U21jMApCpKlgerX5mi%2FEhD5QwZSjqdAEYdVUdf6C9sN7E558XxrPtyqNA00lJImYUjPM%2BFQ78hQ0Y4ADjFQO7p7IAXcYRkGErSfuh7Cx8cBZJS0DGDkaoxAHwHqQq9DsWKvDxu6O2hBgR20cJoE9z8hV2%2B6Qp1YhgKytYXM9oO5fTBi6ARpm6Q55W41bKm92%2FCR2w%2FTGyI%2FNSHQ5I%2BFhRkaXMjKMwA51skPUOZWROM6CFMEQpVGiP8PQsdLU529ASYjelpLYS7hfC6qzPdHwVcfG9USxcJe1qpaQO2Q8Bmkj8vihKxNFpfKT6ZixPG94v6%2Fm4mr0c9mwvFDjaLUbBiw6orRrm3nDQzzuhf8ZlVPkxmwI%2FMoJxXvq2%2FAKhVPi%2BXHIVdis6vbQi%2BJSO%2BxJuTSe6m8qOirn6vK29ry7jbjwotoXHTifHKt9jwVbFB4vipXO8D7LALDs3TOhjnftPcCS1vJKrs%2BSIDGBof10kRCDANkP9oABYxQA7GuwcZKEQWw%2F2eWwST3YPKj9YXMmDW5u0HhbaOA9x6sfhIXsYHFm4vetGrtaNZaTuthQ6aTyK%2FGrr%2FTE6kvQUjH61b20vQQtHW6t0PFrpXZNChM5hn7SEYuKd%2Fe77xRUolHa3MH8r4JKqPKNXfLi5GeJMd3l0i3IvFOQoSsm%2F9YbFkSm9c85ESf1I05H%2FFMPfCiBBw98OL3wwHehgVMPgChJg9SmjHsADBMQpNaTJa6ZnvPg99yiIP%2FMJkhVz5m4FW3Xia%2BZe6kXY%2Ff2Lfxpwql%2FfB%2B9kjm%2FAeFKQMAQBlm8cWqUfBBcRJ7vbxet75h1T8qtXSJ1kis6M7mmh29T0aW3qShzfw7E2femz0zlxzhT6RgkAMeom4qVPt%2F%2BBw61IY7VKEkOThom%2BND4y38QiW88%2FZg8xWfyNDvMU3wxT6MdZF%2Fnd0iY%2FojfITE6j6Y4uypNVXP7t7J2%2BPa%2Fe3j0Hw%3D%3D)) |
| update.js | [update](https://app.diagrams.net/?lightbox=1&highlight=0000ff&edit=_blank&p=update#R7Vtdc6s2EP01fu2AxOdj6ps0fbgzd5rptK8yyFgNII8s28n99RUgbIREbGIDdhs%2FZMxqJaFzdle7kjOD8%2BztN4bWq%2B80xukMWPHbDH6bAeA7jvhbCN4rgWu7lSBhJK5E9lHwQn5iKbSkdEtivFEUOaUpJ2tVGNE8xxFXZIgxulfVljSVs8rx1yjBikYheIlQqkv%2FIjFfVdIAeEf5MybJqp7Z9sKqZYGi14TRbS7nmwG4LD9Vc4bqseSLbFYopvvGpPBxBueMUl59o4t%2FivUBK0ULAbEcs%2Bi5XceI4z%2BZFMY4o82G33OO2Q7JVmBZckLSBKKcInub41Sw91Q9ii9yUqXVavG2RgznvLmWp44O8n3Fu2wluvMUkUyInlEepyRPxNcfjEZ4s5Gg8PeaiM2eZCnKxdOvK8rIT5rzck2WEGw4YlzaDiwES5Kmc5pSVvaFy3Dp47hUZPQVN1qgB0NYtOhrkcvbYcbxW5sXYe6YZpizd6HyVkNb9ZCWDuXjvmE2gZStGibj1IQgaarJYWTQ5ELCaYYWdkL7HeXCRlkvPK8BH%2BgLnwkv14AXuAZeroaXBpDoIIJMgc9%2BRTh%2BWaOoaNmLMFdgxrMCLbtAS0D3hDKSFsQ%2F43SHOYmQbJBWaQP53ADPKj9CjlKS5EIW4cJVTTgHYAE9T2cmdnEQO0b8YV%2F8HdV8A1ejAxrYgP3JMEWyhy0vrRDPisgK7QIWacHHSKb4Zc3koedBXWW8wWh%2Fsy7jd6FTEn0FkMMWyLrN25YxRvRG%2BVT09jQP%2BFtzAbai2WK7uQkX8KIAL5YGF0A4WEbXYeeQdUzjA%2Bs1o7tPeEDV7y7sH3g34wD%2BlwPoe3AwlgNodARn7MixSM3lI2Ui7Cc0R%2BnjUdoNwYZuWYSVvV%2FkjAnmXZsIsIrZPsSM4RRxslOd8hIIwtEgMK23iYc3FQR1AB4BA89gBq1IOgkC9mgI6MttguFPhoBeJw6FgD92KCi7PjCG3hsKa0pyvmmM%2FKMQNKJy6CpR2W2V2S11u5XJq%2BriSzX%2FkYvDQs7NVP7AO4L3vROVqttd5CluOxOcLk8Bujt8JSoenCxRMZy1DBWeWg6jBqp62sED9Ie1iiXe8ZfPlizV%2BnB8FyHBa%2BfGE4YEvXgfygTrkQ1pksbeFMnCVxlnMNXAmi46jlfHdZuhEiavnseasy7fVzG328fU1avLXh%2Bkb354YqBqddpAp1M5%2FdZgvEzblGpr29vEeXZgq3m2fSLRdluHWfZlmbZGj6Ox8xBFYlvjSDJ%2FF%2Fc5EpzDtc0Q9zumFOWxjMDHzOQb4mh2KjEpO0mUSZ7UfUbMS5y%2BODu3c6Rq6xb7n9uMe%2FPjTnemap9zzfmJ%2BO7o8b3DcdSAX9vHJCXLfIWj177xoOx0X%2FFAK40njAcD1SkG%2B6tNq2luHeRNUabY%2F4Mypbel%2Bu50kXGgMsVgmZ1WqETG6U7bz7l1uu%2BfwvQ2zCnr54EuwEwh01CS1dYwvh3Cge69zlx4Z%2F4ycU3qe62a1DtRk7YuLlr6F9ek9kCn30Cn6Y5YatdgdYLVxVJbH8gbvmuxZDg6GIolU%2BJ1awc7Hmg5UXDKicLL9K3rOt1Qvwwx0FnL7sHrPL%2FXvbgThh%2BoX0wSHGjnNpF0R6ExcG6KpPG2L8Pvi26VI%2BCqHEHrou1IPB7%2Fb6VSP%2F5vEHz8Fw%3D%3D) | Adds data-driven diagrams in chromeless mode ([source code](https://app.diagrams.net/plugins/update.js), [example](https://app.diagrams.net/?lightbox=1&highlight=0000ff&edit=_blank&p=update#R7Vtdc6s2EP01fu2AxOdj6ps0fbgzd5rptK8yyFgNII8s28n99RUgbIREbGIDdhs%2FZMxqJaFzdle7kjOD8%2BztN4bWq%2B80xukMWPHbDH6bAeA7jvhbCN4rgWu7lSBhJK5E9lHwQn5iKbSkdEtivFEUOaUpJ2tVGNE8xxFXZIgxulfVljSVs8rx1yjBikYheIlQqkv%2FIjFfVdIAeEf5MybJqp7Z9sKqZYGi14TRbS7nmwG4LD9Vc4bqseSLbFYopvvGpPBxBueMUl59o4t%2FivUBK0ULAbEcs%2Bi5XceI4z%2BZFMY4o82G33OO2Q7JVmBZckLSBKKcInub41Sw91Q9ii9yUqXVavG2RgznvLmWp44O8n3Fu2wluvMUkUyInlEepyRPxNcfjEZ4s5Gg8PeaiM2eZCnKxdOvK8rIT5rzck2WEGw4YlzaDiwES5Kmc5pSVvaFy3Dp47hUZPQVN1qgB0NYtOhrkcvbYcbxW5sXYe6YZpizd6HyVkNb9ZCWDuXjvmE2gZStGibj1IQgaarJYWTQ5ELCaYYWdkL7HeXCRlkvPK8BH%2BgLnwkv14AXuAZeroaXBpDoIIJMgc9%2BRTh%2BWaOoaNmLMFdgxrMCLbtAS0D3hDKSFsQ%2F43SHOYmQbJBWaQP53ADPKj9CjlKS5EIW4cJVTTgHYAE9T2cmdnEQO0b8YV%2F8HdV8A1ejAxrYgP3JMEWyhy0vrRDPisgK7QIWacHHSKb4Zc3koedBXWW8wWh%2Fsy7jd6FTEn0FkMMWyLrN25YxRvRG%2BVT09jQP%2BFtzAbai2WK7uQkX8KIAL5YGF0A4WEbXYeeQdUzjA%2Bs1o7tPeEDV7y7sH3g34wD%2BlwPoe3AwlgNodARn7MixSM3lI2Ui7Cc0R%2BnjUdoNwYZuWYSVvV%2FkjAnmXZsIsIrZPsSM4RRxslOd8hIIwtEgMK23iYc3FQR1AB4BA89gBq1IOgkC9mgI6MttguFPhoBeJw6FgD92KCi7PjCG3hsKa0pyvmmM%2FKMQNKJy6CpR2W2V2S11u5XJq%2BriSzX%2FkYvDQs7NVP7AO4L3vROVqttd5CluOxOcLk8Bujt8JSoenCxRMZy1DBWeWg6jBqp62sED9Ie1iiXe8ZfPlizV%2BnB8FyHBa%2BfGE4YEvXgfygTrkQ1pksbeFMnCVxlnMNXAmi46jlfHdZuhEiavnseasy7fVzG328fU1avLXh%2Bkb354YqBqddpAp1M5%2FdZgvEzblGpr29vEeXZgq3m2fSLRdluHWfZlmbZGj6Ox8xBFYlvjSDJ%2FF%2Fc5EpzDtc0Q9zumFOWxjMDHzOQb4mh2KjEpO0mUSZ7UfUbMS5y%2BODu3c6Rq6xb7n9uMe%2FPjTnemap9zzfmJ%2BO7o8b3DcdSAX9vHJCXLfIWj177xoOx0X%2FFAK40njAcD1SkG%2B6tNq2luHeRNUabY%2F4Mypbel%2Bu50kXGgMsVgmZ1WqETG6U7bz7l1uu%2BfwvQ2zCnr54EuwEwh01CS1dYwvh3Cge69zlx4Z%2F4ycU3qe62a1DtRk7YuLlr6F9ek9kCn30Cn6Y5YatdgdYLVxVJbH8gbvmuxZDg6GIolU%2BJ1awc7Hmg5UXDKicLL9K3rOt1Qvwwx0FnL7sHrPL%2FXvbgThh%2BoX0wSHGjnNpF0R6ExcG6KpPG2L8Pvi26VI%2BCqHEHrou1IPB7%2Fb6VSP%2F5vEHz8Fw%3D%3D)) |
| replay.js | [replay](https://app.diagrams.net/?p=replay&lightbox=1&replay-delay=1000&replay-data=7VjBcpswEP0arh4sbJwcE9fOJemh7kzPCqxBjUBUiGD69V0JYeOAGad1p24G2wzSW+0iaZ+fJBxvKSEQMmRp5Hgrx1vmiiqoi8nuQdIsfhIh8BqRQqjGtgTOHeKy0PE+OYS4eDlkfcI6NVY3oxJSdZaDX3u8Ul5ADX2G0tFePscI989YiHRBQsZp1cAYcW/RD+RFxNI6VK4qbkNJUaQh6EdNsV0ZMwWbjAbaWuKQEYtVwq15yzhfCi6k8fW2c/1FPFdSvEDL4puPtsQ0FCWCLlYCkbDAhoo4zXOL1+7fWKhiRIh+kEjVmiaMVwgsjRtxNzTN8fa0sQ027Kfu5tQzAzRTBFLB7uQ8G6jJJ4gElMTZcq0Dces8uJVtbfPilrZjJhcWi4FFsQ3bYDSv69E+9CGrWLCJbaoHAhnbW34h2OIfworWxTspMccNVWLGw2VM0wj6xookwuTuWiw7QbGbDsU6RIEwgo2tCqliEYmU8tUBvT9QyT2mzXdQqrLZooUSCB0iPAqRXZ5eF6OUHvYwoXCWRCGDppX9tyoqI2iaLfqJJ4FTxV6P47+PRccU+A1WTAdYseiw4hGUnq9KFKb7Wi51l9NwMpmM0nK2tJC/Ky09pEC0JRxYaynKJcSFnKZRM9ZRXP5cXBY94nJ7veLiDYjLbYcVqCHNDsalpnFgHqMnUaQaxCtkNJI0GcXmbLHxPpzYzAfEZtqh1VeB9SLXYRmGvBupc5I6s3O2wOSjUscb16kLrVMN1l6njrYIV7ZO+QOsIB1WPIjW4VuvSbGErTH5Pwp9qMO0qyw3UrPGX1mWk1DScsKEGcRap3p/VrcuzUk9BgmtEzw9nOB9mmgtSp9zfRv33O/Ust4993+tZYsB1s5HLbuUlpEeLZtdr5bdDLBi1rfnDjgLXhBd7ZTEvhLshfvFHu1HdTlTXXo32f9MXfTrxda77F8=) | Adds _Extras > Record_ for replaying all changes made to a diagram |
| anonymize.js | [anon](https://app.diagrams.net/?splash=0&p=anon) | Adds _Extras > Anonymize Current Page_ to remove metadata and change labels, including the page name ([how to use](/doc/faq/anonymize-plugin.html))|
| webcola.js | [webcola](https://app.diagrams.net/?splash=0&p=webcola) | Adds _Layout > WebCola Layout_ to run the interactive, constraint-based layout |
| tickets.js | [tickets](https://app.diagrams.net/?splash=0&p=tickets) | Adds _Extras > Update Tickets_ to drop Freshdesk tickets into diagrams ([example](https://jgraph.github.io/drawio-tools/tools/tickets.html)) |
| flow.js | [flow](https://app.diagrams.net/?splash=0&p=flow) | Adds _Toggle Flow_ to the context menu, and a connector click handler to the lightbox |
| tags.js | [tags](https://app.diagrams.net/?splash=0&p=tags)	 | Adds _Extras > Tag Cloud_ for visual tag filtering and assignment ([how to use](/doc/faq/tags-plugin.html)) |

**Note:** Plugins are not supported in draw.io for Confluence.