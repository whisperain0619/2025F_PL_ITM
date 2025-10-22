# 2025F_PL_ITM
#ex 1
# TODO: Your code here
# 파일을 불러옵니다.
with open('yesterday.txt', 'r') as f:
    yesterday_lyric = f.read()
yesterday_lyric_num = yesterday_lyric.lower().count("Yesterday")


print(f"Yesterday 개수: {count}" )

#ex2
# TODO: Your code here
with open('yesterday.txt', 'r') as f:
    yesterday_lyric = f.read()

for p in string.punctuation:
    text = text.replace(p, " ")
words = text.split()

COUNT = words.count("Yesterday")
count = words.count("yesterday")
print(f"Yesterday 개수: {COUNT}" )
print(f"yesterday 개수: {count}" )
