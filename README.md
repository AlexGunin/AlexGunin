<style>
ul>li {
  list-style:none;
}
li>img {
  margin-right:10px;
  }
</style>

### Hi there👋
My name Alex. I am frontend-developer
<hr>
<h3>About me</h3>
<ul>
  <li style="list-style:none;">I crazy about write code especially from solving problems on <b>codewars</b> / <b>leetcode</b></li>
  <li><img src="https://cdn3.iconfinder.com/data/icons/education-science-vol-1-1/512/reading_book_read_learn-256.png" style="width:25px, margin-right:10px"/>I am constantly learning new things</li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
</ul>
const [improveToday, setImproveToday] = useState({})

const createMyself = (previous, new = {}) => {...previous, ...new}

const remembering = (data) => setImproveToday(prev => {...prev, ...data})

setTimeout(function createMyself(){

}, 1000)
//today
