# Association-Rules

What are Association Rules? --> Method used to reveal product relationships from user purchases. It provides the opportunity to see the unity of products purchased according to a threshold value to be determined.


It is a rule-based machine learning technique used to find patterns (relationships, structures) in data. Also known as __Market Basket Analysis__.

Association Rules applications are among the most common applications in data science. It will also come across as recommendation systems.

You may have come across these applications in the following ways: "those who bought that product also bought this product" or "those who viewed that ad also looked at these ads" or "we created a playlist for you" or "the recommended video for the next video".

These scenarios will be the most common scenarios within the scope of e-commerce data science data mining studies.

Many e-commerce companies around the world or companies, platforms like Spotify, Amazon, Netflix use recommendation systems.

So what do these association analyzes do?

__Apriori Algorithm__

It is the most used method in this field.

Association rule analysis is performed by examining some metrics:

X: product 

Y: product 

N: total shopping / order / transaction

__Support__: Probability of X and Y coexisting

- Support (X, Y) = Freq(X, Y) / N


__Confidence__: Probability of selling product Y when product X is purchased

- Confidence (X, Y) = Freq(X, Y) / Freq(X)

__Lift__: The sales of the first product increases the sales of the second product by 'Lift' times.

- Lift = Support (X, Y) / ( Support(X) * Support(Y) )
