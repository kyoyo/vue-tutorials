# basic-props.html

1. define local component[my-component] which contains props:[]
2. add <template id="myComponent"></template>
3. <my-component></my-component>


# simple-demo.html

1. define component[simple-grid]
   props {data:Array,columns:Array,filterKey:String}

2. new Vue {data:{searchQuery,gridColumns,gridData} }

  gridData: [{
  					name: 'Jack',
  					age: 30,
  					sex: 'Male'
  				}, {
  					name: 'Bill',
  					age: 26,
  					sex: 'Male'
  				}, {
  					name: 'Tracy',
  					age: 22,
  					sex: 'Female'
  				}, {
  					name: 'Chris',
  					age: 36,
  					sex: 'Male'
  				}]

3. <template id ="grid-template"></template>

4. <simple-grid :data= :columns= :filter-key=></simple-grid>



