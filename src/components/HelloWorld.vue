<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      我是一名来自山西太原的深大学生，目前就读计算机技术专业，希望通过自身努力，争取更大进步，让自己以后的生活更美好！
    </p>
    <h3>基本信息</h3>
    <ul>
      <li>学号：2310273032</li>
      <li>姓名：杨轶超</li>
    </ul>
    <h3>学习经历</h3>
    <ul>
      <li>
        <table cellpadding="5" cellspacing="5">
          <tr align="left">
            <td>2019.09-2023.06</td> 
            <td>广西师范大学</td> 
            <td>计算机科学与技术 </td>
            <td>工学学士</td>
          </tr>
          <tr align="left">
            <td>2023.09-至今</td> 
            <td>深圳大学</td>
            <td>计算机技术</td>
            <td>硕士在读</td>
          </tr>
        </table>
      </li>
    </ul>
    <h3>联系方式</h3>
    <ul>
      <li>QQ：1150696064</li>
      <li>E-mail：2310273032@email.szu.edu.cn</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
