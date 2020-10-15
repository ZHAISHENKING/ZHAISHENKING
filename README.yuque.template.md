<h2>我的书单 <img src="https://github.githubassets.com/images/mona-whisper.gif" height="24" /></h2>
<p align="right">迷茫的时候，抬头看看天</p>

{{#each record}}
  - [{{title}} ( {{short created_at "MM-dd"}} · {{math likes_count "*" 7}} 颗稻谷)](https://yuque.com/{{@root.namespace}}/{{slug}})
{{/each}}
