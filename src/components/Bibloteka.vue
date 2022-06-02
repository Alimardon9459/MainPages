<template>
  <div class="q-pa-md">
    <q-table
      title="Our library"
      class="my-sticky-header-column-table"
      :rows="rows"
      :columns="columns"
      row-key="name"
      :rows-per-page-options="[0]"
      fullscreen
    />
  </div>
</template>


<script>
export default {
    data() {
        return {
            columns:[
                {
                    name: 'name',
                    required: true,
                    label: 'Yozilishi',
                    align: 'left',
                    field: row => row.name,
                    format: val => `${val}`,
                    sortable: true
  
                },
                { name: 'type', align: 'center', label: 'Nomi', field: 'type', sortable: true },
                { name: 'size', label: 'O\'chov berish', field: 'size', sortable: true },
                { name: 'interval', label: 'Qiymatlar Oralig\'i', field: 'interval' },
                { name: 'distance', label: 'O\'sish oralig\'i ', field: 'distance' },
            ] , 
            rows:[
                //width
                {  
                    name: "w-100px",
                    type:"w---width",
                    size:"100px---100px",
                    interval:"1px-1000px",
                    distance:"1px"
                    
                },
                {  
                    name: "w-100pr",
                    type:"w---width",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%"
                    
                },
                //height
                {  
                    name: "h-100px",
                    type:"h---height",
                    size:"100px---100px",
                    interval:"1px-1000px",
                    distance:"1px" 
                },
                {  
                    name: "h-100vh",
                    type:"h---height",
                    size:"100vh---100vh",
                    interval:"1vh-100vh",
                    distance:"1vh" 
                },
                {  
                    name: "h-100pr",
                    type:"h---height",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                //margin
                {  
                    name: "m-100px",
                    type:"m---margin",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "m-100pr",
                    type:"m---margin",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                //margin top
                {  
                    name: "mt-100px",
                    type:"mt---margin-top",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "mt-100pr",
                    type:"mt---margin-top",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "mt-m100pr",
                    type:"mt---margin-top",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                 // margin bottom
                {  
                    name: "mb-100px",
                    type:"mb---margin-bottom",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "mb-100pr",
                    type:"mb---margin-bottom",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "mb-m100pr",
                    type:"mb---margin-bottom",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                //margin right
                {  
                    name: "mr-100px",
                    type:"mr---margin-right",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "mr-100pr",
                    type:"mr---margin-right",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "mr-m100pr",
                    type:"mr---margin-right",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                // margin left 
                {  
                    name: "ml-100px",
                    type:"ml---margin-left",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "ml-100pr",
                    type:"ml---margin-left",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "ml-m100pr",
                    type:"ml---margin-left",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                // padding
                {  
                    name: "p-100px",
                    type:"p---padding",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "p-100pr",
                    type:"p---padding",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                //padding top
                {  
                    name: "pt-100px",
                    type:"pt---padding-top",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "pt-100pr",
                    type:"pt---padding-top",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "pt-m100pr",
                    type:"pt---padding-top",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                 // padding bottom
                {  
                    name: "pb-100px",
                    type:"pb---padding-bottom",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "pb-100pr",
                    type:"pb---padding-bottom",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "pb-m100pr",
                    type:"pb---padding-bottom",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                //padding right
                {  
                    name: "pr-100px",
                    type:"pr---padding-right",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "pr-100pr",
                    type:"pr---padding-right",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "pr-m100pr",
                    type:"pr---padding-right",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                // padding left 
                {  
                    name: "pl-100px",
                    type:"pl---padding-left",
                    size:"100px---100px",
                    interval:"1px-500px",
                    distance:"1px-200px --- 1px ; 200px-500px --- 10px  " 
                },
                {  
                    name: "pl-100pr",
                    type:"pl---padding-left",
                    size:"100pr---100%",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                {  
                    name: "pl-m100pr",
                    type:"pl---padding-left",
                    size:"m100pr---(-100%)",
                    interval:"1%-100%",
                    distance:"1%" 
                },
                //font-size
                {
                    name:"fs-50px",
                    type:"fs---font-size",
                    size:"50px---50px",
                    interval:"1px-100px",
                    distance:"1px"
                },
                //letter-spacing
                {
                    name:"ls-50px",
                    type:"ls---letter-spacing",
                    size:"50px---50px",
                    interval:"1px-50px",
                    distance:"1px"
                },
                //line-height
                {
                    name:"lh-2_1",
                    type:"lh---line-height",
                    size:"2_1---2_1",
                    interval:"1-4",
                    distance:"0.1"
                },
                //border-radius
                {
                    name:"br-50px",
                    type:"br---border-radius",
                    size:"50px---50px",
                    interval:"1px-50px",
                    distance:"1px"
                },

                {
                    name:"br-50pr",
                    type:"br---border-radius",
                    size:"50pr---50%",
                    interval:"1%-50%",
                    distance:"1%"
                },
                //display-flex
                { 
                    name:"d-f", 
                    type:"display: flex", 
                }, 
                { 
                    name:"jc-sp_aro", 
                    type:"justify-content: space-around", 
                }, 
                { 
                    name:"jc-sp_btw", 
                    type:"justify-content: space-between", 
                }, 
                { 
                    name:"jc-sp_eve", 
                    type:"djustify-content: space-evenly", 
                }, 
                { 
                    name:"jc-center", 
                    type:"justify-content: center", 
                }, 
                { 
                    name:"jc-end", 
                    type:"justify-content: end", 
                }, 
                { 
                    name:"jc-left", 
                    type:"justify-content: left", 
                }, 
                { 
                    name:"jc-right", 
                    type:"justify-content: right", 
                }, 
                { 
                    name:"jc-start", 
                    type:"justify-content: start", 
                }, 
                { 
                    name:"jc-stretch", 
                    type:"justify-content: stretch;", 
                }, 
                { 
                    name:"jc-baseline", 
                    type:"justify-content: baseline", 
                }, 
                { 
                    name:"jc-flx-end", 
                    type:"justify-content: flex-end", 
                }, 
                { 
                    name:"jc-flx-start", 
                    type:"justify-content: flex-start", 
                }, 
                { 
                    name:"jc-unset", 
                    type:" justify-content: unset", 
                }, 
                { 
                    name:"ai-baseline", 
                    type:"align-items: baseline", 
                }, 
                { 
                    name:"ai-center", 
                    type:"align-items: center", 
                }, 
                { 
                    name:"ai-flx_end", 
                    type:"align-items: flex-end", 
                }, 
                { 
                    name:"ai-flx_start", 
                    type:"align-items: flex-start", 
                }, 
                { 
                    name:"ai-stretch", 
                    type:"align-items: stretch", 
                }, 
                { 
                    name:"ai-inherit", 
                    type:"align-items: inherit", 
                }, 
                { 
                    name:"ai-initial", 
                    type:"align-items: initial", 
                }, 
                { 
                    name:"ai-unset", 
                    type:"align-items: unset", 
                }, 
 
            ]
        }
    },
}
</script>

<style lang="sass">
.my-sticky-header-column-table
  /* height or max-height is important */
  

  /* specifying max-width so the example can
    highlight the sticky column on any browser window */
  max-width: 100%

  td:first-child
    /* bg color is important for td; just specify one */
    background-color: #c1f4cd !important

  tr th
    position: sticky
    /* higher than z-index for td below */
    z-index: 2
    /* bg color is important; just specify one */
    background: #fff

  /* this will be the loading indicator */
  thead tr:last-child th
    /* height of all previous header rows */
    top: 48px
    /* highest z-index */
    z-index: 3
  thead tr:first-child th
    top: 0
    z-index: 1
  tr:first-child th:first-child
    /* highest z-index */
    z-index: 3

  td:first-child
    z-index: 1

  td:first-child, th:first-child
    position: sticky
    left: 0

</style>
