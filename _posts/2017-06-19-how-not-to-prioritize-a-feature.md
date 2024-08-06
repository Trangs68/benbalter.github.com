---
title: How not to prioritize a feature
description: The hardest part of software development is not coming up with features to build, but instead, deciding what features will have the biggest impact.
---

Sometimes, great ideas, customer needs, product priorities, and engineering resources align perfectly. Sometimes, a feature is so simple that it makes more sense to implement it than to take the time to prioritize or sequence it. In my experience, those features represent the vast minority of features. In a world of near-endless possibilities (and limited developer hours), the most challenging part of software development is not coming up with features to build but instead deciding what features will have the most significant impact. Here are seven antipatterns I've seen, both in open and closed source, for prioritizing feature requests:

### Someone is willing to build it

In less formal organizations (open source projects included), the most significant barrier to entry is finding someone with the skills necessary to solve an identified problem. Open source issue trackers are replete with "this is a great idea if anyone is willing to submit a pull request"-type issues. The same applies to non-developer stakeholders and closed-source projects, with lawyers, support reps, and marketers shopping around ideas internally to find someone willing to implement them.

Maybe the idea comes from a developer who's experienced the problem themselves. Perhaps the external issue or internal ask makes its way in front of a sympathetic engineer willing to dedicate a few cycles. Granted, there will always be no-brainers and quick wins, but in most cases, "someone is willing to do this" should not necessarily translate to "we should do this."

### Sales say a lot of/a big/a potential customer is asking for it

Your Sales team is one of your most robust means of getting customer feedback. If an existing or potential customer has a suggestion, it's in everyone's best interest for that idea to be communicated via the sales rep to those in a position to implement it. But it's all too easy to confuse that which you hear from an important customer with that which is most important. Sure, there may occasionally be overriding business concerns, but in general, product development and project management are neither a democracy nor a pure customer oligarchy.

Your users are experts at using your product, not building, supporting, or maintaining it. Feedback via your sales channels should be one of your primary means of understanding user challenges, and it may make sense to consider logos or seats. Still, it should not be your primary means of feature definition or prioritization, nor your only means of feedback.

### Your friend is asking for it

People in technology tend to have friends in technology. It's not uncommon for friends to be users and for conversations at meetups, over dinner, or during happy hour to turn to talk shop. Nobody wants to disappoint someone they respect, and showing that you listened to their advice or were in a position to implement their suggestion is a proven recipe to garner admiration.

Unless you're building a product for developers, it's unlikely that your friends are your target audience, and even if you are, they're not going to be representative of the full range of both current and potential users. Friends can be the source of some of your most honest, direct, and immediate critical feedback, but remember that one data point does not create a pattern.

### It's easy to do it

There will always be a certain number of trivial, no-brainer, quick wins to implement and serve as "quality of life" improvements for users. When you're looking at adding a toggle to turn off a feature or supporting a one-off workflow, it can be tempting to click merge, especially when the depth of discussion becomes disproportionate to the technical lift.

Just because something's easy to implement doesn't mean that you necessarily should. For one, every feature you add creates an implicit and perpetual contract with your users, a contract that obligates you to maintain, support, and build around that feature in every subsequent release. For another, [a well-curated project is a feature in itself](https://ben.balter.com/2016/07/21/removing-a-feature-is-a-feature/). Sometimes, taking the time to implement the technically more complex solution will ultimately be better for users and maintainers.

### Your competitor does it

Any sufficiently complex choice between two pieces of software will at least partially hinge on a feature bake-off in which you create a matrix comparing the offerings of two or more alternatives. If you know this is how you will be evaluated, and it can be tempting to try to stack the deck in your favor by checking every box you can so that you objectively win on arithmetic alone.

Ultimately, a single feature may make or break a deal, but in the long run, if that feature's not part of your core value proposition, users are going to choose you over your competitor based on taste, vision, and direction, not on your ability to export to PDF, especially if you give them the means to build a workaround. Instead of cramming for the midterm exam, focus on what you do best overall, not on what your competitor does today.

### A squeaky wheel is asking for it

There's always that user. There's a pet feature they want. Maybe they're the only ones experiencing it. Perhaps it's something you've deprioritized for other reasons. Whatever the reason, they're not taking "no" for an answer, and they use every opportunity they can to remind you of it. Whether emailing weekly, using hyperbolic language with support or sales, or threatening to move to a competitor, you know you will continue to be bombarded by requests until you give in.

Product development is not a shouting match. Just because someone shouts an idea loudly or often doesn't mean it's a good one. You may be tempted to fulfill the request to please the customer (or end the request DoS), but more often than not, as soon as you do, they'll have another equally critical feature to fixate on next. Sometimes, genuinely take-it-or-leave-it features may make business sense to implement, but I've often found it's the customer, not the product, and it may be worth taking the risk that they realize it's just not the right fit. Everyone will ultimately be better off.

### A handful of power users are asking for it

Most products have three broad classes of users: new users, mainstream users, and power users. New users need your product to be as simple and intuitive as possible. They are also often the metric by which you measure growth. As they go deeper and deeper into your product, power users want to implement increasingly complex and custom workflows. Power users are most invested in your product and can be your strongest advocates. You want a product that encourages growth, but you don't want to force users out as they mature or cannibalize one group to make things more sticky for the other.

It can be hard to balance two seemingly opposed use cases but keep in mind that for every power user that writes in asking for a feature, there's one new user (and ten potential users) that felt the opposite way but is still onboarding and didn't have enough at stake to warrant letting you know. If you're trying out an app and see something you don't like, you move on to the next app. That's not the case if you've been using it for years and have a high switching cost. When you're evaluating potential features, part of your role is to be an advocate for the long tail of users who won't yet advocate for themselves.

### Conclusion

What features should you build, then? In short, you should focus on themes that support a more unified product vision and the individual features that build towards them before a feature request comes in. You should know who your target users are, the use cases you'd like to support, and roughly the direction you want your product heading towards in six months or a year.

Great product ideas come from unexpected sources and at unpredictable times. Software is more art than science, and sometimes, it takes getting one feature into the hands of users to realize you need another. While it may be tempting to shortsightedly tackle features that are easy to implement or loudly requested, when ideas do come in, they should be evaluated against established product themes, not what requests make sense in isolation or now.
