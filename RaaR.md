# RaaR Rev 1.0 Standard
Research as a Repo  
Revision 1.0
5 May 2024

## Directory Structure
```
/ README.md
/ research
- / 0001.txt
- / 0002.txt
- / ...
- / 9999.txt
```

Every repository must have a `README.md` in the root directiry. This `README.md` should contain the project name, a description, the author(s), contact information, and the RaaR revision / version it uses (These can be stated in any particular order, but in a friendly and readable way).

Every repository must have a `/research` directory or one that  is similarly titled or descriptively-named.

Inside of the `/research` directory must be numerical reference text documents going in order from `0001.txt` to `9999.txt`.

**Note that the file extension can either be `.txt` or `.md`, as long as it is consistant across all of the documents.**\

This standard does not yet define what to do when the upper limit is reached. It is recommended that you use 5 places instead of 4 if the limit is reached, or break up your research paper into an anthology if you have ten-thousand references.

## Reference Document Structure

Every reference document should have the following structure:

Spec.:
```
[Researcher's last name], [Researcher's first name] [Researcher's middle initial or full name].
[Source author's last name], [Source author's first name] [Source author's middle initial or full name].
[Full title of the publication as is presented by the author, or its commonly known name].
[Publication day] [Unabbreviated publication month] [Publication year].
[Entire url including protocol://, full hostname, full pathname, filename, and search (if applicable), but excluding the port and the hash. Use https://url-parts.glitch.me/ if unsure of which parts to include and exclude]
[Name of the website retrieved or organization, whichever is more relevant].

"""
[Direct quote from the original source document in which the reference uses.]
"""

[Optional: why was this quote used?]
```

Example:
```
Abdul-Ahad, Caden Joseph.
Doe, Jane E.
A brief history of the steam engine.
1 April 2024.
https://www.example.com/
Example Website

"""
The history of the steam engine is a fascinating journey through innovation and technological advancement. The story begins in the early 18th century with Thomas Newcomen, an English inventor, who created the first practical steam engine in 1712. Newcomen's engine was primarily used for pumping water out of mines and was a significant improvement over previous methods.
"""

First practical steam engine was invented by Thomas Newcomen in 1712.
```

If the `.md` file extension is used, ensure to add `\` at the end of the first lines to ensure newlines are created. Do not use `  `.

Example:
```
Abdul-Ahad, Caden Joseph.\
Doe, Jane E.\
A brief history of the steam engine.\
1 April 2024.\
https://www.example.com/\
Example Website

"""
The history of the steam engine is a fascinating journey through innovation and technological advancement. The story begins in the early 18th century with Thomas Newcomen, an English inventor, who created the first practical steam engine in 1712. Newcomen's engine was primarily used for pumping water out of mines and was a significant improvement over previous methods.
"""

First practical steam engine was invented by Thomas Newcomen in 1712.
```

If the source is not an online source, exclude the URL and website and include:
```
[Publishing company name, or name formatted in the same way as researcher's and source author's if publisher is a human. Follow the same rules for multiple names.]
Vol. [volume, if not applicable, exclude this entire line].
Pg. [page number as formatted in the original source].
```

Example:
```
Abdul-Ahad, Caden Joseph.
Doe, Jane E.
A brief history of the steam engine.
1 April 2024.
Publisher Name
Vol. 1.
Pg. 23.

"""
The history of the steam engine is a fascinating journey through innovation and technological advancement. The story begins in the early 18th century with Thomas Newcomen, an English inventor, who created the first practical steam engine in 1712. Newcomen's engine was primarily used for pumping water out of mines and was a significant improvement over previous methods.
"""

First practical steam engine was invented by Thomas Newcomen in 1712.
```

### Special Cases

If there is no author, replace with:
```
Author unknown.
```

If there are two authors, format as:
```
Doe, Jane E & Doe, John.
```

If there are three authors, format as:
```
Doe, Jane E & Doe, John & Jacobs, Robert.
```

If there are more than three authors, format as:
```
Doe, Jane E et al.
```

For cases with two or more authors, order the authors in the way the original source lists the authors.

If there is no publication title, replace with:
```
Untitled work.
```

If there is no day, format as:
```
April 2024.
```

If there is no month, format as:
```
2024.
```

If there is no year, replace with:
```
Unknown date.
```
