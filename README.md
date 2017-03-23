# Word-Frequency---Python
Counting the unique words coming from a file



## From this:
[![screenshot_1490298494.png](https://s19.postimg.org/4f4dxprg3/screenshot_1490298494.png)](https://postimg.org/image/pos08k7qn/)
## To this:
[![screenshot_1490298350.png](https://s19.postimg.org/6v67bk9ir/screenshot_1490298350.png)](https://postimg.org/image/um5kto9pr/)


### Regular Expressions:
```
match_pattern = re.findall(r'\b[a-z]{3,15}\b', final_text)
```
### Collecting the Words:
[![screenshot_1490298684.png](https://s19.postimg.org/a4kmi0xmb/screenshot_1490298684.png)](https://postimg.org/image/bjm76qypb/)


### plotting the Words:
```
# Plot histogram using matplotlib bar()
plt.xlabel('Top 10 Words')
plt.ylabel('Frequency')
plt.title('Plotting Word Frequency')
indexes = np.arange(len(words_names) )
width = .4
plt.bar(indexes, words_count, width)
plt.xticks(indexes + width * .4, words_names)
#plt.legend()
plt.tight_layout()
plt.show()
```
