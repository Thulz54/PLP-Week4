try:
    with open("input.txt", "r") as infile:
        content = infile.read()
except FileNotFoundError:
    print("Error: input.txt file not found. Please create it first with at least five lines of text.")
    exit()

word_count = len(content.split()) 
uppercase_content = content.upper() 

with open("output.txt", "w") as outfile:
    outfile.write("Processed Text:\n")
    outfile.write(uppercase_content + "\n\n")
    outfile.write(f"Word Count: {word_count}\n")
    
    def calculate_discount(price, discount_percent):
        
        pass

    print("Success! The file output.txt has been created with the processed text and word count.")
