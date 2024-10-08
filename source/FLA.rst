附录A  超声波检测仪的率定和维护
=====================================

.. raw:: html

  <h2 id="test111">附录A  超声波检测仪的率定和维护</h2>


A.1 一般规定
-------------------------------------------  

.. raw:: html

 <p style="text-align:justify"><a href="#idA.1.1"> A.1.1</a> <span id="idA.1.1"> 超声波检测仪应符合现行行业标准《水运工程 非金属声波检测仪》(JT/T 576)的规定。</span></p>

 <p style="text-align:justify"><a href="#idA.1.2"> A.1.2</a> <span id="idA.1.2"> 正常情况下，超声波检测仪校准周期宜为一年。</span></p>

 <p style="text-align:justify"><a href="#idA.1.3"> A.1.3</a> <span id="idA.1.3"> 当出现下列情况之一时，应对超声波检测仪进行校准：</span></p>
  <ol>
  <li>新仪器启用前；</li>
  <li>检测数据异常，无法进行调整；</li>
  <li>经过维修或更换零配件；</li>
  <li>遭受严重撞击或其他损害。</li>
 </ol>

 <p style="text-align:justify"><a href="#idA.1.4"> A.1.4</a> <span id="idA.1.4"> 操作人员应熟悉仪器使用说明书，掌握其操作方法。</span></p>

 <p style="text-align:justify"><a href="#idA.1.5"> A.1.5</a> <span id="idA.1.5"> 每次工程检测前，应进行超声波检测仪的率定并测定声时值初读数。</span></p>



A.2 率定
-------------------------------------------  

.. raw:: html

 <p style="text-align:justify"><a href="#idA.2.1"> A.2.1</a> <span id="idA.2.1"> 超声波检测仪的率定宜在室温为（15~25）℃，相对湿度不大于75%的条件下进行。</span></p>

 <p style="text-align:justify"><a href="#idA.2.2"> A.2.2</a> <span id="idA.2.2"> 率定过程中应确保仪器电压稳定，周围应无影响正常工作的强烈电磁场干扰及机械振动。</span></p>

 <p style="text-align:justify"><a href="#idA.2.3"> A.2.3</a> <span id="idA.2.3"> 率定前，应调节超声波检测仪的基线、首波控制线及屏幕幅度刻度，使波形显示区清晰和稳定。</span></p>

 <p style="text-align:justify"><a href="#idA.2.4"> A.2.4</a> <span id="idA.2.4"> 平面换能器应与超声波检测仪连接，并悬挂于率定装置，将两个换能器的辐射面相互对准放置，见<a href="#figA.2.4">图A.2.4</a></span></p>

 <div align="center"><img id="figA.2.4" src="./_static/fig/A.2.4.png" alt="Picture" width="400px"></div>
  <p style="color: dimgray;text-align: center;">图A.2.4 超声披检测仪率定装置<br/>1－定滑轮；2－螺栓；3－刻度尺；4－支架；5－发射换能器；6－接收换能器；7－超声波检测仪</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figA.2.4'));</script>



 <p style="text-align:justify"><a href="#idA.2.5"> A.2.5</a> <span id="idA.2.5"> 轻拉上挂于定滑轮中的电缆线，两换能器的问距宜为25 mm、50 mm、100 mm、150 mm···，读取相应声时值<i>t</i><sub>1</sub>、<i>t</i><sub>2</sub>、<i>t</i><sub>3</sub>、<i>t</i><sub>4</sub>...，测试数据不应少于5个。两换能器间距的测量误差不应大于±0.5%。同时应测量空气温度。 </span></p>

 <p style="text-align:justify"><a href="#idA.2.6"> A.2.6</a> <span id="idA.2.6"> 空气声速可采用下列方法求得：</span></p>

 <ol>
 <li>以测距为纵坐标，以声时读数为横坐标，绘制声时值一测距坐标图，见<a href="#figA.2.6">图A.2.6</a>，坐标图中直线AB的斜率<math xmlns="http://www.w3.org/1998/Math/MathML" ><mi mathvariant="normal">Δ</mi><mi>l</mi><mrow><mo>/</mo></mrow><mi mathvariant="normal">Δ</mi><mi>t</mi></math>即为空气声速的推定值；</li>
 <li>按<a href="#ideqA.2.6">式(A.2.6)</a><span id="ideqA.2.6">求出回归直线方程，回归直线方程的回归系数b为空气声速的推定值，精确至0.01 km/s</li> 
 </ol>

 <div align="center"><img id="figA.2.6" src="./_static/fig/A.2.6.png" alt="Picture" width="400px"></div>
  <p style="color: dimgray;text-align: center;">图A.2.6 空气声速时一距图</p>
  <script type="text/javascript">var viewer = new Viewer(document.getElementById('figA.2.6'));</script>

$$l_{i}=a+bt_{i}\\tag{A.2.6}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="50px" align='right' id="eqzs"><i>l</i><sub>i</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">第<i>i</i>点测距（mm），精确至1 mm；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs" align='right' ><i>t</i><sub><i>i</i></sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">第<i>i</i>声时值（μs），精确至0.1 μs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs" align='right' ><i>a、b</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">回归系数。</td>
 </tr> 
 </table>
 <p></p>



 <p style="text-align:justify"><a href="#idA.2.7"> A.2.7</a> <span id="idA.2.7"> 空气声速标准值应按<a href="#ideqA.2.7">式(A.2.7)</a><span id="ideqA.2.7">计算。</span></p>


$$v_{\\mathrm{c} }=331.4\\sqrt{1+0.00367T_{\\mathrm{k} }} \\tag{A.2.7}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='left' id="eqzs"><i>v</i><sub>c</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">空气声速标准值（km/s），精确至0.01 km/s；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>T</i><sub>k</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">室温（℃）。</td>
 </tr>
 </table>
 <p></p>

 <p style="text-align:justify"><a href="#idA.2.8"> A.2.8</a> <span id="idA.2.8"> 空气声速推定值与空气声速标准值间的误差应按<a href="#ideqA.2.8">式(A.2.8)</a><span id="ideqA.2.8">计算。</span></p>


$$\\xi _{\\mathrm{r} }=\\dfrac{v_{\\mathrm{c} }-v_{\\mathrm{s} }}{v_{\\mathrm{c} }}\\times 100\\%\\tag{A.2.8}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='left' id="eqzs"><i>ξ</i><sub>r</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">空气声速推定值与空气声速标准值间的误差（km/s），精确至0.01 km/s；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>v</i><sub>c</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">空气声速标准值（km/s），精确至0.01 km/s；</td>
 </tr> 
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>v</i><sub>s</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">空气声速推定值（km/s），精确至0.01 km/s。</td>
 </tr>
 </table>
 <p></p>



 <p style="text-align:justify"><a href="#idA.2.9"> A.2.9</a> <span id="idA.2.9"> 测试误差满足<a href="#ideqA.2.9">式(A.2.9)</a><span id="ideqA.2.9">时可判为合格，反之则判为不合格。</span></p>

$$\\xi _{\\mathrm{r} }\\leqslant \\pm 0.5\\%\\tag{A.2.8}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="30px" align='left' id="eqzs"><i>ξ</i><sub>r</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">空气声速推定值与空气声速标准值间的误差（km/s），精确至0.01 km/s。</td>
 </tr>
 </table>
 <p></p>

A.3 声时值初读数的测定
-------------------------------------------  

.. raw:: html

 <p style="text-align:justify"><a href="#idA.3.1"> A.3.1</a> <span id="idA.3.1"> 平面换能器声时值初读数的测定可选用下列方法之一：</span></p>
  <ol>
  <li> 将换能器直接精合，读取声时值初读数，按<a href="#ideqA.3.1.1">式(A.3.1-1)</a><span id="ideqA.3.1.1"> 计算声时值初读数。</li>
 </ol>

$$t_{0}=t_{\\mathrm{k}}+t\\tag{A.3.1-1}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="20px" align='left' id="eqzs"><i>t</i><sub>0</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">声时值初读数（μs），精确至0.1 µs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>t</i><sub>k</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">开机显示声时值初读数（μs），精确至0.1 µs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>t</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">测试所得声时值（μs），精确至0.1 µs。</td>
 </tr>  
 </table>
 <p></p>



  <ol start="2">
  <li> 将换能器搞合于标准棒上，读取声时值，按<a href="#ideqA.3.1.2">式(A.3.1-2)</a><span id="ideqA.3.1.2">计算声时值初读数。</li>
 </ol>

$$t_{0}=t_{\\mathrm{k} }+t-t^{'}\\tag{A.3.1-2}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="20px" align='left' id="eqzs"><i>t</i><sub>0</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">声时值初读数（μs），精确至0.1 µs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>t</i><sub>k</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">开机显示声时值初读数（μs），精确至0.1 µs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>t</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">测试所得声时值（μs），精确至0.1 µs；</td>
 </tr> 
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>t</i><sup>'</sup></td>
 <td id="eqzs">——</td>
 <td id="eqzs">标准棒的声时值（μs），精确至0.1 µs。</td>
 </tr>   
 </table>
 <p></p>

 <p style="text-align:justify"><a href="#idA.3.2"> A.3.2</a> <span id="idA.3.2"> 径向换能器声时值初读数应采用声时值一测距法测定。两个径向换能器应保持轴线平行，置于同一非金属水槽的饮用水中同一水平高度，先将两个换能器内边缘间距<i>l</i><sub>1</sub>调节在200 mm的位置，再将两个换能器内边缘间距<i>l</i><sub>2</sub>调节在100 mm的位置，分别读取相应声时值<i>t</i><sub>1</sub>、<i>t</i><sub>2</sub>。声时值初读数<i>t</i><sub>0</sub>应按<a href="#ideqA.3.2">式(A.3.2)</a><span id="ideqA.3.2">计算。</span></p>


$$t_{0}=(l_{1}t_{2}-l_{2}t_{1})/(l_{1}-l_{2})\\tag{A.3.2}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="50px" align='left' id="eqzs"><i>t</i><sub>0</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">声时值初读数（μs），精确至0.1 µs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>l</i><sub>1</sub>、<i>l</i><sub>2</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">两个换能器内边缘间距（mm），精确至1 mm；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>t</i><sub>1</sub>、<i>t</i><sub>2</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">测试所得声时值（μs），精确至0.1 µs。</td>
 </tr>  
 </table>
 <p></p>


 <p style="text-align:justify"><a href="#idA.3.3"> A.3.3</a> <span id="idA.3.3"> 径向换能器在同一混凝土结构或构件的两个混凝土钻孔中对测时的声时值初读数<i>t</i><sub>2</sub><sup>'</sup>；应按<a href="#ideqA.3.3">式(A.3.3)</a><span id="ideqA.3.3">计算。</span></p>

$$t_{0}^{'}=t_0+(d_1-d)/v_{\\mathrm{w} }\\tag{A.3.3}$$

.. raw:: html

 <table border="0" style="font-family:times new roman" id="gongshi">
 <tr>
 <td width="50px" align='center' id="eqzs">式中</td>
 <td width="20px" align='left' id="eqzs"><i>t</i><sup>'</sup><sub>0</sub></td>
 <td width="40px" align='left' id="eqzs">——</td>
 <td id="eqzs">钻孔中测试的声时值初读数（μs），精确至0.1 µs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>t</i><sub>0</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">声时值初读数（μs），精确至0.1 µs；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>d</i><sub>1</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">声测孔直径（mm），精确至1 mm；</td>
 </tr>  
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>d</i></td>
 <td id="eqzs">——</td>
 <td id="eqzs">径向换能器直径（mm），精确至1 mm；</td>
 </tr>
 <tr>
 <td id="eqzs"> </td>
 <td id="eqzs"><i>v</i><sub>w</sub></td>
 <td id="eqzs">——</td>
 <td id="eqzs">水中超声波速度（km/s），可按<a href="#BA.3.3">表A.3.3</a>取值。</td>
 </tr>  
 </table>
 <p></p>


.. raw:: html

      <style>
     #biaoge {
         border: 2px solid black;
         border-collapse: collapse;
         margin-bottom:1px;
        
      }
      th, td {
         padding-top: 5px;
         padding-bottom:5px;
         padding-left:5px;
         padding-right:5px;
         border: 1px solid black;
         
      }
      #eqzs {
         border: 0px;
      }
      #dhbg {
        vertical-align: middle;
      }
     </style>

		<table id="biaoge" style="font-family:times new roman">

         <caption style="caption-side:top;text-align: center;color:black" ><b style="text-align:center"> <div id="BA.3.3">表A.3.3 水中超声波速度</b></caption>	
              
		    <tr>
		     <td  align="center" width="300px" id="dhbg">水温度（℃）</td>
		     <td  align="center" width="100px" id="dhbg">5</td>
				 <td  align="center" width="100px" id="dhbg">10</td>
         <td  align="center" width="100px" id="dhbg">15</td>
		     <td  align="center" width="100px" id="dhbg">20</td>
				 <td  align="center" width="100px" id="dhbg">25</td>
         <td  align="center" width="100px" id="dhbg">30</td> 
		    </tr>
		    <tr>
		     <td align="center" >水中超声波速度（km/s）</td>
         <td align="center" >1.45</td>
         <td align="center" >1.46</td>
         <td align="center" >1.47</td>
         <td align="center" >1.48</td>
         <td align="center" >1.49</td>    
         <td align="center" >1.50</td>
		    </tr>
		</table>
 <p></p>



 <p style="text-align:justify"><a href="#idA.3.4"> A.3.4</a> <span id="idA.3.4"> 径向换能器在预埋声测管中检测时的声时值初读数应按<a href="#ideqA.3.4">式(A.3.4)</a><span id="ideqA.3.4">计算。</span></p>




 <p style="text-align:justify"><a href="#idA.3.5"> A.3.5</a> <span id="idA.3.5"> 当采用一只平面换能器和一只径向换能器进行检测时，声时值初读数可取平面换能器声时值初读数和径向换能器声时值初读数之和的1/2。</span></p>


A.4 维护
-------------------------------------------  

.. raw:: html

 <p style="text-align:justify"><a href="#idA.4.1"> A.4.1</a> <span id="idA.4.1"> 发现仪器工作不正常时，应停止工作。</span></p>

 <p style="text-align:justify"><a href="#idA.4.2"> A.4.2</a> <span id="idA.4.2"> 仪器不得在有强腐蚀性气体环境或强电磁干扰的环境下工作。</span></p>

 <p style="text-align:justify"><a href="#idA.4.3"> A.4.3</a> <span id="idA.4.3"> 仪器使用完毕后，应清除传感器、导线上的油污、尘土，仪器各配件均应妥善放于仪器箱内，放于通风和干燥环境。每隔3个月宜通电2 h。</span></p>

 <p style="text-align:justify"><a href="#idA.4.4"> A.4.4</a> <span id="idA.4.4"> 仪器在使用及搬运过程中应防止冲击。</span></p>




:math:`\ ` 