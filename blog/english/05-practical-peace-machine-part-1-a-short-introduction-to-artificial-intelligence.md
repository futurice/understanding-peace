# Practical Peace Machine, Part 1: A short introduction to artificial intelligence

Futurice has been investigating artificial intelligence and peace tech in a project called Peace Machine. Timo Honkela, the father of the Peace Machine -concept, describes that his ideas are for the future. Something that cannot be done today. However we wanted to understand how far can we get with today’s technologies.

This blog post in divided into two parts. In this first part we’ll discuss what AI is and what is it good for. In part two we’ll take a deep dive into the concepts of the Peace Machine to understand how far we could implement them.

## So, what is artificial intelligence?

Artificial intelligence (AI) is about machines making autonomous decisions based on the data it perceives from its surroundings. The data could be from another computer system, added by a human or measured with sensors.

Quite often you hear people talking about algorithms and the word has become almost a synonym for AI. But not all algorithms are intelligent. An algorithm is generally just a set of rules or instructions.

Try it out: Waving as an algorithm
1. Raise your arm
1. Move your arm left
1. Move your arm right
1. Repeat from step 2

For intelligent algorithm you need more than just instructions. The algorithm should interpret its surroundings, the data, and be able to choose the actions based on it.

You can approach AI in two ways. Either you make a set of precise rules on how the system should work, or you allow the system to learn from previous data. The latter approach is also known as machine learning (ML).

For example, if we would like to create a system that predicts the eye color of children based on their parents’ eyes, we can define: if both parents have blue eyes, the child will likely have blue eyes as well. If either of the parents have brown eyes, the children will likely have brown eyes. (The truth is not as straightforward, but we can use this for our example.)

The ML approach would be to gather a data set with parents, children and everyone’s eye colors. The algorithm would then calculate a set of probabilities for child’s eye color based on the eye colors of parents.

## Choosing the approach

Both approaches have good and bad sides. Some phenomenons are so complicated that describing them with simple rules would be either extremely difficult or simply impossible. Spoken language is a good example of such phenomena. That’s why NLP (natural language processing) tools often use ML.

On the other hand, using ML is far from perfect. The results are at best as good as the teaching data. Is the amount of data sufficient? Do we have some systematic error in the teaching data? The more sensitive data the system is using, the more important these questions become.

Think about a banking system that defines whether a person is given loan or not. The system is taught using history data of loans given and declined. If the bank would’ve historically given more declines to a certain postal code area than others, the algorithm couldn’t reason why the people in that specific area have been declined. It would just assume that postal code is an important factor in loan decisions, and decline any future requests from the given area.

These kind of biases in machine learning systems are not at all rare.

It is up to creators of the services to make sure that the systems avoid biases. When we talk about peace tech it is hugely important not to have a system that divides people in an unjust manner. Bad teaching data might actually cause the system to worsen the situation rather than making it better.

You can also combine the two approaches. For sensitive data, if it’s needed in the first place, it’s better to choose rule based approach. For non-sensitive and complex phenomena we can use ML systems. Together the algorithms can form better systems than just strictly keeping to one or another.

## Be specific to get results

A lot of AI utopias might give people the idea that machines are very close to human intelligence. This is very far from the truth. In fact, AI performs best (if not only) in very restricted tasks.

Computers don’t work like humans. Human brains have specialized in handling concepts that can have complex connections to one another. Computers don’t have concepts. Computers look at data points like numbers, letters and words. They can see connections between data points but don’t understand why the connection is there.

With enough data, an AI system could answer questions like: “Girl is to queen the same as what is to king?” It should find the connections and answer “Boy is to king the same as girl is to queen”. But unlike a human, who could see connections in gender and status, the computer only sees that these words are used similarly.


For the Peace Machine it's important to understand that AI systems have different approaches, they work best in restricted environments, and are better at seeing details than describing entities from data. In the second part we'll dig deeper into the Peace Machine concept and discuss how these theories would like in practice.
