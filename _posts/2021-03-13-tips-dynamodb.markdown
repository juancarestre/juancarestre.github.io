---
layout: post
title: Lo que nadie te dice de DynamoDB
category: category-1
image: assets/img/Comonocagarla-dynamodb.jpg
image_alt: Post image cover
summary: DynamoDB 
---
[Jekyll](https://jekyllrb.com/) Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse efficitur turpis nec tortor sagittis, in tincidunt lectus iaculis. Sed tempor ligula ac nulla dictum, quis luctus tortor pretium. Suspendisse vitae nibh id sapien tempus posuere eu id ante. Fusce nec neque nisl. Suspendisse velit elit, euismod et lacus a, commodo mollis ligula. Duis non nibh gravida, interdum tellus sed, aliquam libero. Ut et tempor velit. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

<iframe width="1050" height="500" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


### Test of syntax highlights
{% highlight shell linenos %}
# bash
$ gem build THEME_NAME.gemspec
$ gem push THEME_NAME-*.gem
$ ls -l
$ cd ..
{% endhighlight %}


{% highlight javascript linenos %}
// javascript
try {
    const { name } = req.params;
    if (name === 'make_it_fail') {
        throw Error('User triggered failure');
    }
    Logger.Info(DemoController.SUCCESS_MSG + name);
    return res.status(OK).json({
        message: DemoController.SUCCESS_MSG + name,
    });
} catch (err) {
    Logger.Err(err, true);
    return res.status(BAD_REQUEST).json({
        error: err.message,
    });
}
{% endhighlight %}

{% highlight C# %}
/*
    C#
*/
var hype = getHype();
return hype.toList();
{% endhighlight %}

{% highlight python %}
# python
def getTimeTicks(spacing, sampleRate, secLength):
    ticks = [0]
    fullSecs = int(math.floor(secLength))

    for t in np.arange(3, fullSecs - 3, 3):
        ticks.append(t*sampleRate/spacing)
    ticks.append(int(secLength*sampleRate/spacing) - 1)

    return ticks
{% endhighlight %}


Aliquam tempor porttitor mi. Aliquam et sapien faucibus, mattis purus sed, malesuada urna. Ut eget enim urna. Duis tempus est vel tincidunt luctus. Nunc commodo ante nec orci scelerisque, eu lobortis massa fermentum. Nunc sagittis eros at sapien volutpat aliquet. Donec posuere efficitur laoreet. Ut ornare tellus ut ipsum hendrerit, vitae varius ante pharetra. Suspendisse fringilla leo erat, dignissim auctor ex ultrices a. Sed ultrices blandit eros. Pellentesque volutpat ultrices sem, vel semper enim fermentum eu. Nulla eget eros ipsum. Sed hendrerit et arcu vitae pulvinar. Vivamus facilisis, eros eu gravida rhoncus, enim felis suscipit leo, vitae lacinia magna nisl hendrerit est. Cras eget blandit ante. Aenean tincidunt blandit lacus, vitae porta ipsum viverra et.

Proin urna lorem, pulvinar quis orci non, accumsan pharetra erat. Aliquam vulputate aliquam tellus, ac sollicitudin nibh fermentum in. Sed malesuada nisl mi, vitae lobortis massa pretium ut. Nunc risus diam, consectetur non congue sed, rutrum eu eros. Integer sed aliquet sapien, a porttitor ex. Nam sed auctor augue, vitae cursus arcu. Donec vehicula viverra scelerisque.

Duis quis mattis eros, gravida convallis dui. Nullam venenatis nisi mauris, eu consequat purus fermentum non. Suspendisse libero ipsum, tristique non efficitur ultrices, fringilla vulputate purus. Nullam laoreet lacus non sapien euismod, in viverra augue feugiat. Integer congue varius risus at cursus. Aenean tincidunt arcu vitae massa eleifend porta. Nullam facilisis eros rhoncus metus tincidunt tempus. Maecenas viverra urna mi, id rhoncus lectus aliquet maximus. Pellentesque vulputate turpis ut nulla lobortis, at ullamcorper sem sodales. Phasellus fringilla neque ut libero condimentum fermentum. Sed lobortis, felis mollis porta lacinia, nibh neque maximus ante, non eleifend dolor nunc dictum velit. Sed lacinia ut quam et dapibus.