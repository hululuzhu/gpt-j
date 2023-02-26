# Use gpt-j to get Chinese input and expect programming code output
Use GPT-J (small GPT-3) to test AI coding ability
- Update 02/2023: TPU version is too broken to be fixed, switched to premier GPU version

# Notes
1. I only tested zero short learning (no example in prompt), ideally with examples, the result is better.
2. The test cases for different languages are randomly picked without a systematic plan, so treat the examples as fun result instead of real performance benchmark.
3. I have created a simple inference method for custom top_p and temperature, with sampling turned on by default
