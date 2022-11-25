# complaw
comprehensible version of finnish law

# Tasklist

- [x] Define the technology that will be initially used to create this and why
- [ ] Figure out how the finlex.fi api for laws works
- [ ] Re-read the society studies book on how laws works
- [ ] Write a crawler for finlex.fi
- [ ] Modify the text so that the reader does not have to open n pages for full read on it
- [ ] Learn how to simplify text automatically
- [ ] Simplify the law text

# API of finlex.fi (/fi/laki/{parameter})

- /ajantasa

you can search this endpoint by the year or by the topic or by the number

- /alkup

you can search this endpoint by the year or by the number

- /kokoelma

you can search this endpoint by the year or by the number

- /smur

you can search this endpoint by the year or by the number

- /kaannokset

you can search this enpoint by the year or by the number or by the language

- /saame

this endpoint only has a list of links straight to pdf files

# Tech used to make this

- Operating system: Ubuntu Server 22.04.1
- Main Language: C
- Why: I want to create an easy CLI tool to read all the latest law and I also want to learn C