# Use gpt-j to get Chinese input and expect programming code output
Use GPT-J (small GPT-3) to test AI coding ability

# Notes
1. I only tested zero short learning (no example in prompt), ideally with examples, the result is better.
2. The test cases for different languages are randomly picked without a systematic plan, so treat the examples as fun result instead of real performance benchmark.
3. I set topp=0 and temperature=1.0 for re-produce. Play with the params to try different inference options if you like to seriously test.
4. The official colab seems to miss some imports, I have to manually inserted.
5. It seems the current version of TF+Transformer stopped working since 08/20, have to downgrade to TF2.3
