<script>function handRowEvent(ev,table){
		$("td.tdNo",table).each(function(i){
			$(this).text(i+1);
		});
	}</script>
<p>
    <br/>
</p>
<table cellpadding="2" cellspacing="0" border="1" class="formTable" parser="addpermission" style="width:960px;margin:0 auto">
    <tbody>
        <tr class="firstRow">
            <td colspan="2" class="formHead" style="border:1px solid #fff;border-bottom: 3px solid red !important;color: red;background-color:#fff;font-family:����;letter-spacing: 6px;font-size:25px;">
                �����Ҫ
            </td>
        </tr>
        <tr>
            <td align="right" nowrap="nowarp" style="width:20%;background-color:#fff;border:1px solid #fff;border-bottom: 1px solid red;" class="formTitle">
                �������:
            </td>
            <td class="formInput" style="width:80%;border:1px solid #fff;border-bottom: 1px solid red;1px solid #fff">
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<input parser="inputtable" type="text" name="m:hyjy:hybt" lablename="�������" class="inputText" value="" validate="{maxlength:50}" isflag="tableflag"/>
            </td>
        </tr>
        <tr>
            <td align="right" nowrap="nowarp" style="width:20%;background-color:#fff;border:1px solid #fff;border-bottom: 1px solid red;" class="formTitle">
                ������Ա:
            </td>
            <td class="formInput" style="width:80%;border:1px solid #fff;border-bottom: 1px solid red;1px solid #fff">
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<input parser="selectortable" name="m:hyjy:cyry" type="text" ctltype="selector" class="users" lablename="������Ա" value="" validate="{empty:false}" readonly="readonly" scope="{&#39;type&#39;:&#39;system&#39;,&#39;value&#39;:&#39;all&#39;}"/>
            </td>
        </tr>
        <tr>
            <td align="right" nowrap="nowarp" style="width:20%;background-color:#fff;border:1px solid #fff;border-bottom: 1px solid red;" class="formTitle">
                ����ʱ��:
            </td>
            <td class="formInput" style="width:80%;border:1px solid #fff;border-bottom: 1px solid red;1px solid #fff">
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<input parser="datetable" name="m:hyjy:hysj" type="text" class="Wdate" lablename="����ʱ��" displaydate="0" datefmt="yyyy-MM-dd" value="" validate="{empty:false}"/>
            </td>
        </tr>
        <tr>
            <td align="right" nowrap="nowarp" style="width:20%;background-color:#fff;border:1px solid #fff;border-bottom: 1px solid red;" class="formTitle">
                ����ص�:
            </td>
            <td class="formInput" style="width:80%;border:1px solid #fff;border-bottom: 1px solid red;1px solid #fff">
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<input parser="inputtable" type="text" name="m:hyjy:hydd" lablename="����ص�" class="inputText" value="" validate="{maxlength:100}" isflag="tableflag"/>
            </td>
        </tr>
        <tr>
            <td align="right" nowrap="nowarp" style="width:20%;background-color:#fff;border:1px solid #fff;border-bottom: 1px solid red;" class="formTitle">
                ������:
            </td>
            <td class="formInput" style="width:80%;border:1px solid #fff;border-bottom: 1px solid red;1px solid #fff">
                &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<input parser="selectortable" name="m:hyjy:sqr" type="text" ctltype="selector" class="user" lablename="������" value="" validate="{empty:false}" readonly="readonly" scope="{&#39;type&#39;:&#39;system&#39;,&#39;value&#39;:&#39;all&#39;}" showcuruser="1"/>
            </td>
        </tr>
    </tbody>
</table>
<p>
    <br/>
</p>