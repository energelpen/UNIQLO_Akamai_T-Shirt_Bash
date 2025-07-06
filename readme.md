# UNIQLO × Akamai T-Shirt Collaborations

## Overview

My favourite Japanese fashion brand called UNIQLO collaborated again with a tech company called Akamai to design a T-shirt.

The first shirt they made was written in Golang: [UNIQLO Akamai Go T-Shirt Code Repository](https://github.com/GL-Kageyama/UNIQLO_Akamai_T-shirt_Code). However, this new shirt was written in base64 obfuscated shellscript which was pretty cool.

Out of the box, I somehow was not able to make it to run immediately. I had to manually copy the base64 string and decode it and then run it as shellscript which was cool.

## Cool T-Shirt Colab


At first glance when I looked at it in the Uniqlo store, it looked like a jumble of text, but then I noticed it’s actually a **Base64-encoded shell script**. When you decode it, it’s a simple bash script that prints out a pretty sweet messages.

```plaintext
Hello World!
This is a bash
script converted to base64!
Pay attention to the details hell hidden in this code when you find these strings!
Give love, receive love and spread love!
You've found the secret message!
PEACE FOR ALL - Encoded with love!
```

It’s like a hidden little message for anyone who knows how to decode Base64 and run bash scripts. I love how they mixed fashion with a little programming puzzle — it’s like wearing a secret message only fellow tech nerds can fully appreciate.

If you’re curious (like I was), you can easily decode the script yourself and see the message pop up in your terminal. Honestly, it feels so satisfying to uncover these kinds of Easter eggs. I have included both the Original Shellscript and the Decoded Shellscript as well as the base64 encoded text in the repo if you are interested in having a look. Peace out yo!