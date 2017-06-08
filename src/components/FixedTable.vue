<template>
    <div class="left-fixed-wrap" id="fixedTable">
        <table class="left-fixed-table">
            <tr>
               <th class="fixed-col">序号</th>
               <th class="placeholder-col"></th>
               <th>姓名</th> 
               <th>出生日期</th> 
               <th>年龄</th> 
               <th>性别</th> 
               <th>爱好</th> 
               <th>描述</th>
               <th>姓名</th> 
               <th>出生日期</th> 
               <th>年龄</th> 
               <th>性别</th> 
               <th>爱好</th> 
               <th>描述</th>
            </tr>
            <tr>
                <td class="fixed-col">000001</td>
                <td class="placeholder-col"></td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
            </tr>
            <tr>
                <td class="fixed-col">000001</td>
                <td class="placeholder-col"></td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
            </tr>
            <tr>
                <td class="fixed-col">000001</td>
                <td class="placeholder-col"></td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
            </tr>
            <tr>
                <td class="fixed-col">000001</td>
                <td class="placeholder-col"></td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
            </tr>
            <tr>
                <td class="fixed-col">000001</td>
                <td class="placeholder-col"></td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
                <td>俄云花</td>
                <td>1992.03.19</td>
                <td>25</td>
                <td>女</td>
                <td>看电影、运动</td>
                <td>随便写写好了呢</td>
            </tr>
        </table>
    </div>
</template>

<script type="text/javascript">
    
</script>

<style lang="less">
    .left-fixed-wrap {
        width: 400px;
        overflow-x: auto;
        border-right: 1px solid #dedede;
        .left-fixed-table {
            border-collapse: collapse;
            tr {
                position: relative;
                th,td {
                    border: 1px solid #dedede;
                    overflow: hidden;
                    white-space: nowrap;
                    text-overflow: ellipsis;
                    height: 36px;
                    line-height: 36px;
                    &:last-child {
                        border-right: 0 none;
                    }
                    &.fixed-col {
                        position: absolute;
                        background: #fff;
                        width: 100px;
                    }
                    &.placeholder-col {
                        width: 100px;
                        display: inline-block;
                        border-right: 0 none;
                        border-bottom: 0 none;
                    }
                }
            }
        }
    }
</style>
