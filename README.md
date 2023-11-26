# Abai
A dataset of works by **[Abai Qunanbaiuly](https://en.wikipedia.org/wiki/Abai_Qunanbaiuly)** (1845 – 1904), a great Kazakh poet, composer, and philosopher
```
BBBBBBBBBBBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBBBBBBBBBBBB
BBBBBBAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBBBBBBBBBB
BBBBBAAAAAAAAAAAAAAAAAAAAAAAAAAABBBBBABBBBBBBAAAAAAAAAAAAAAAAAAAAAAAABBBBBBBBBBB
BBBAAAAAAAAAAAAAAAAAAAAAAAAAABBAAAAAAAAABBBBBAAAAAAAAAAAAAAAAAAAAAAAAABBBBBBBBBB
AAAAAAAAAAAAAAAAAAAAAAAAAAABBAAAAAAAAABBBBBBBAAAAAAAABBBAAAAAAAAAAAAAAAABBBBBBBB
AAAAAAAAAAAAAAAAAAAAAAAAAABBAAABBBAAAAAAAAAAAAAAAAAAABBBBBAAAAAAAAAAAAAAAABBBBBB
AAAAAAAAAAAAAAAAAAAAAAAABBAABBAAIIIIIIIIIIIIIIIIIIAABBBBBBBBAAAAAAAAAAAAAAAABBBB
AAAAAAAAAAAAAAAAAAAAIIABBBAAAAAIIIIIIIIIIIIIIIIIIIIIIAABBBBBBAAAAAAAAAAAAAAAABBB
AAAAAAAAAAAAAAAAAIIIIABBAAAAAAIIIIIIIIIIIIIIIIIIIIIIIIIIABBBBAAAAAAAAAAAAAAAAABB
AAAAAAAAAAAAAAAIIIIIIABAAAABAAIIIIIIIIIIIIIIIIIIIIIIIIIIIABBBBAAAAAAAAAAAAAAAAAB
AAAAAAAAAAAAAAIIIIIIABAAAAAAAAIIIIIIIIIIIIIIIIIIIIIIIIIIIABAABAAAAAAAAAAAAAAAAAA
AAAAAAAAAAAAAIIIIIIIBBAAAABBBBBBAAAIIIIIIIIIIIIIAAAAAAIIIIBBABAIIAAAAAAAAAAAAAAA
AAAAAAAAAAAIIIIIIIIIBBAAAAAAAAAAAABBAAIIIIIAAABBBAAAAAAIIIAAABBAIIAAAAAAAAAAAAAA
AAAAAAAAAAAIIIIIIIIABAAAABBBBBAAIIIIABAIIIAAAABAIIIIIAAAIIIAABBAIIAAAAAAAAAAAAAA
AAAAAAAAAAAIIIIIIIIABAAAAABBBBBBBAAAAABIIIAABBBBBAAAAAAAIIIIBBBAIIIAAAAAAAAAAAAA
AAAAAAAAAAIIIIIIIAAAAAAAAIAABAAAAIIAAABIIIIAAAABAIAABBAAAIIIAAAAIIIAAAAAAAAAAAAA
AAAAAAAAAIIIIIIIIBBAAAAAAAAAAAAAAAAABBAIIIIIIAAAAAIIIAAAIIIIABIAAIIIAAAAAAAAAAAA
AAAAAAAAAIIIIIIIIBABAABBAAIIIIIIIIABBBAIIIIIIIIIIIIIIIIIIIIIAAABBAIIAAAAAAAAAAAA
AAAAAAAAIIIIIIIIIAABAABBAAIIIIIIIIABBBAIIIIIIAIIIIIIIIIIIIIIAAAAAAIIAAAAAAAAAAAA
AAAAAAAAIIIIIIIIIIABAABBBAAIIIIIAAABBBAAIAAIIAAAIIIIIIIIIIAAAAAAAIIIAAAAAAAAAAAA
AAAAAAAAIIIIIIIIIIAAAAAABAAAIIIABBABAABBAABAIIIAAIIIIIIIIAAAAAAAAIIAAAAAAAAAAAAA
AAAAAAAAAIIIIIIIIIIAAAAAAAAAAAAABBBBBBAAAAAAIIIIIIIIIIAAAAAAAAAAIIIAAAAAAAAAAAAA
AAAAAAAAAIIIIIIIIIIIAAAAAAAAAAABBBBBBAAAAAAAAAAIIIIIIIAAAAAAAIAIIIIAAAAAAAAAAAAA
AAAAAAAAAIIIIIIIIIIIIIAAAAAAAABBBAAAABBABBBBBABIIIIAAAAAAAAAAAAIIIIAAAAAAAAAAAAA
AAAAAAAAAAIIIIIIIIIIIAAAABBBAABBAAABBBAAAAAABBBAIAIAAAAAAAAAIIIIIIAAAAAAAAAAAAAA
AAAAAAAAAAIIIIIIIIIIABAAAABBBBBBAAAABBBBBAAABBBBAAAAAAAAAAAAIIIIIIAAAAAAAAAAAAAA
AAAAAAAAAAAIIIIIIIIIBBBAAABBBBBABBBBBBABBAAABBBBBAAAAAAAAAAIIIIIIAAAAAAAAAAAAAAA
AAAAAAAAAAAAIIIIIIIAAABBAAABBBBBBBABAAAAAIIIAAABAAAAAAAAAAIIIIIIAAAAAAAAAAAAAAAA
AAAAAAAAAAAAAAAAABBAAAABBBAAABBBABAAIIIIIIIIAIAAIIAAAAAAAAIIIIIAAAAAAAAAAAAAAAAB
AAAAAAAAAAAABBBAAAAAAAAABBBAABBBBBBAAAIIAAIIIAIIIIIAAAAAAAAAAAAAAAAAAAAAAAAAAAAB
AAAAAAABBBAAAAAAAAAAAAAABAABBABBABBBBBAAAAAAAAIIIIIABAAAAAAABBBBBAAAAAAAAAAAAABB
ABBBBAAAAAAAAAAAAAAAAAABBBAABBBBABBBBBAAAAAAAAAAIIABAAIAIABAABBBBBBBBBBBBBAAABBB
BAAAAAAAAAAAAAAAAAAAAAABBBBBABBBAAABABAAIIABAAAIIAAAAAAAIABBAABBBBBBBBBBBBBBBBBB
AAAAAAAAAAAAAAAAAAAAABBBBBBBBBBBAAABBABAIIABAAAIAAAAAAAIAABBBBBBBBBBBBBBBBBBBBBB
AAAAAAAAAAAAAAAAAAAABBBBBBBBBBBBABAABBBBAAAAAAIIAAAAAIIAAABABABBBBBBBBBBBBBBBBBB
AAAAAAAAAAAAAAAAAABBBBBBBBBBBBBBBBBABBBBAAAAAAAAAAAAAAAAAABABAAABBBBBBBBBBBBBBBB
AAAAAAAAAAAAAAAAAAABBAAAABBBBBBBBBBBBBBBBABAAAAAAAAAAAAAAABABBAAAAABBBBBBBBBBBBB
AAAAAAAAAAAAAABAAAAABBAAAAABBBBBBBBBBBBBBAAAAAAAAAABBBBBAABBBAAAAAABBBBBBBBBBBBB
AAAAAAAABBBBBBBBBAAAABBBBBBBBBBBBBBBBBBBAAAAAAAAAAAAAABBBBBBAAAAAAABBBBBBBBBBBBB
AAAAABBBBBBBBBBBBBAAABBBBBBBBBBBBBBBBBBBAAAAAAAAAAAAAAAAABABAAAAAABBBBBBBBBBBBBB
```
# Files

 ## verses_kazakh.csv
 - The file contains 176 verses by Abai Qunanbaiuly.
 - With punctuation and \n removed:
   - the number of tokens in the **KK_Text** column is 19,190.
   - the number of types in the **KK_Text** column is 8,099.
   - the number of unique letters in the **KK_Text** column is 40.
 
 ![The frequency of letters in Abai's verses.](images/verses_letter_frequency.png)
 
  ## verses_translated.csv
 - The file contains 176 verses by Abai Qunanbaiuly (see **verses_kazakh.csv**) and their Russian translations.
 - 168 verses were written in the period between 1855 and 1903; the exact years of eight verses are unknown.
 - 21 verses have no Russian translations.
 - The names of 43 translators head columns (e.g., **A. Zhovtis**,	**A. Kodar**,	**A. Romm**, etc.) after the **Year**, **KK_Title**, and **KK_Text** columns.
 - A translator's name is given more than once (e.g., **A. Steinberg_1**,	**A. Steinberg_2**,	**A. Steinberg_3**) if there are multiple variants of a verse by the same translator.
