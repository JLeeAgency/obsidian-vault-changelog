---
created: 2023-12-09T21:15
updated: 2023-12-10T15:53
---
**« [[<% fileDate = moment(tp.file.title, '[W]ww').subtract(1, 'weeks').format('[W]ww') %>|Last week]] | [[<% fileDate = moment(tp.file.title, '[W]ww').add(1, 'weeks').format('[W]ww') %>|Next week]] »**
# 📅 Agency Weekly Updates
Foreword

## 📈 Production Overview
- **Current Quarter Premium**: $
- **Policies Written This Week**: 
- **Policies Cancelled This Week**: 

## 🚀 Sales Focus
- **Sales Goal for Next Week**: $
- **Sales Tips**: 
- **Lead Source Performance**: 

## 💡 Training and Development
- **This Week's Training Sessions**: 
- **New Hire Progress**: 
- **Continuing Education**: 

## 🛠️ Operational Updates
- **Carriers/Products**: 
- **System Updates**: 
- **Underwriting Memos**: 

## 🗣️ Feedback & Ideas
- **Team Shout-Outs**: 
- **Open Forum**: Share your ideas to improve our agency workflow, customer experience, etc.

## 📌 Action Items for This Week
- [ ] Item 1
- [ ] Item 2
- [ ] Item 3

## 💭 Closing Thoughts

Remember to keep your eye on the prize and the other on your customer. Together, we are unstoppable!

---
### 👀 Notes Created Last Week
```dataview
List FROM "" WHERE file.cday %3E= date("%3C%tp.date.subtract(8, "days").format("YYYY-MM-DD")%%3E") SORT file.ctime asc
```
