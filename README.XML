# Phil
For trade 
```xml
<xml xmlns="https://developers.google.com/blockly/xml" is_dbot="true" collection="false">
  <variables>
    <variable id="1Gp/v]LP27,I/mi@$;US">NAME</variable>
    <variable id="9dQ4tsj$@`vWpu;:2{K=">Stake</variable>
    <variable id="`=|V?TV%1c6]^Pvh=CK/">Loss</variable>
    <variable id="zgaB|[y?n^GAllQO_%AW">text1</variable>
    <variable id="!P]:?:q)?v?}qINF%J42">Win Stake</variable>
    <variable id="=,v,K8he5FCw^;Ui5Ein">list</variable>
    <variable id="KJY)s]gb8kw=?gUi0nK/">text2</variable>
    <variable id="-q:tvpdw7v6S[CTHK{8g">text4</variable>
    <variable id="7/Cs|{m_XjDwo::I6g5A">Random</variable>
    <variable id="#nKyoAm=Zh-Afx.zUa%f">Trend List</variable>
    <variable id=":Fbza.{0*q*jalJ+tc#.">Expected Profit</variable>
    <variable id="BTQ{$u318X:bRnhP(mQ9">Stop Loss</variable>
    <variable id="CH:,y=UW[E4+/t9J5[!h">text3</variable>
    <variable id="qVmX5zUrmm#9(^,=8j9c">text5</variable>
    <variable id="2%u_7^a8rtYPr1vwtnOB">text</variable>
  </variables>
  <block type="trade_definition" id="W6@v=SqCp]mGVi5ml?YH" deletable="false" x="0" y="110">
    <statement name="TRADE_OPTIONS">
      <block type="trade_definition_market" id="nAKp7rF^Gll{%P%/_m#[" deletable="false" movable="false">
        <field name="MARKET_LIST">synthetic_index</field>
        <field name="SUBMARKET_LIST">random_index</field>
        <field name="SYMBOL_LIST">1HZ25V</field>
        <next>
          <block type="trade_definition_tradetype" id="uu(bKSYk(ZT%u,LG7t4x" deletable="false" movable="false">
            <field name="TRADETYPECAT_LIST">digits</field>
            <field name="TRADETYPE_LIST">evenodd</field>
            <next>
              <block type="trade_definition_contracttype" id="pa-_z]%5v^$8nG5T*6XC" deletable="false" movable="false">
                <field name="TYPE_LIST">DIGITODD</field>
                <next>
                  <block type="trade_definition_candleinterval" id="vwin`K{C}Mx9#;l_x:qC" deletable="false" movable="false">
                    <field name="CANDLEINTERVAL_LIST">60</field>
                    <next>
                      <block type="trade_definition_restartbuysell" id="=;^j+^/^lqOgBTnJ4a:=" deletable="false" movable="false">
                        <field name="TIME_MACHINE_ENABLED">FALSE</field>
                        <next>
                          <block type="trade_definition_restartonerror" id="jZz46?e=x!P7PnoSggZ#" deletable="false" movable="false">
                            <field name="RESTARTONERROR">TRUE</field>
                          </block>
                        </next>
                      </block>
                    </next>
                  </block>
                </next>
              </block>
            </next>
          </block>
        </next>
      </block>
    </statement>
    <statement name="INITIALIZATION">
      <block type="variables_set" id="q#LB=b8Lgg^u)kZP=7@P" collapsed="true" disabled="true">
        <field name="VAR" id="1Gp/v]LP27,I/mi@$;US">NAME</field>
        <value name="VALUE">
          <block type="text_prompt_ext" id="a{b8cmUyQu7}gw_yQy}K" collapsed="true">
            <field name="TYPE">TEXT</field>
            <value name="TEXT">
              <shadow type="text" id="UfI;.ZuZXzjh]ukf;#{n">
                <field name="TEXT">Please enter your name</field>
              </shadow>
            </value>
          </block>
        </value>
        <next>
          <block type="variables_set" id="j$`?U$q*+4]dg7_zizE+">
            <field name="VAR" id="9dQ4tsj$@`vWpu;:2{K=">Stake</field>
            <value name="VALUE">
              <block type="math_number" id="ke=M45Puk/sT/j8c!gig">
                <field name="NUM">14</field>
              </block>
            </value>
            <next>
              <block type="variables_set" id="1~E!Kjw$PL9qNq^G`@FE">
                <field name="VAR" id="!P]:?:q)?v?}qINF%J42">Win Stake</field>
                <value name="VALUE">
                  <block type="math_number" id="V|@!j[qO#KSo*}Rd}pUx">
                    <field name="NUM">14</field>
                  </block>
                </value>
                <next>
                  <block type="lists_create_with" id="v*=mg]lWB7$)`PSxV2uZ">
                    <field name="VARIABLE" id="=,v,K8he5FCw^;Ui5Ein">list</field>
                    <next>
                      <block type="variables_set" id=")rme8XB)?)-b!}:ydKHC">
                        <field name="VAR" id="#nKyoAm=Zh-Afx.zUa%f">Trend List</field>
                        <value name="VALUE">
                          <block type="variables_get" id="=C$2S*+umzSb;IV=uH$Z">
                            <field name="VAR" id="=,v,K8he5FCw^;Ui5Ein">list</field>
                          </block>
                        </value>
                        <next>
                          <block type="variables_set" id="UV.{sRZ|VD+f=pu8h24m">
                            <field name="VAR" id=":Fbza.{0*q*jalJ+tc#.">Expected Profit</field>
                            <value name="VALUE">
                              <block type="math_number" id="+2n@r}2wC~@mq}ET;Q-5">
                                <field name="NUM">2000</field>
                              </block>
                            </value>
                            <next>
                              <block type="variables_set" id="VD{YZQ1i5tPSf|4H@9n~">
                                <field name="VAR" id="BTQ{$u318X:bRnhP(mQ9">Stop Loss</field>
                                <value name="VALUE">
                                  <block type="math_number" id="@tnsXy1.@=zDTvet|-5C">
                                    <field name="NUM">10000</field>
                                  </block>
                                </value>
                                <next>
                                  <block type="text_join" id="FyP(8h2Dd[eCwkG[H/N~">
                                    <field name="VARIABLE" id="2%u_7^a8rtYPr1vwtnOB">text</field>
                                    <statement name="STACK">
                                      <block type="text_statement" id="@PE~)|=Ds^%-QIDXZ8:w" collapsed="true" disabled="true">
                                        <value name="TEXT">
                                          <shadow type="text" id="k=]L#)j`WV!HtV?.`[d~">
                                            <field name="TEXT"></field>
                                          </shadow>
                                          <block type="text" id="q0=$/*.jEv7/W(.i,Oo">
                                            <field name="TEXT"> AUTO C4 PRO 1 [BY💵C. E. O FREDDY]•Expected Profit-&gt; $</field>
                                          </block>
                                        </value>
                                        <next>
                                          <block type="text_statement" id=",!s:1n||^.FKjTwf59p-">
                                            <value name="TEXT">
                                              <shadow type="text" id="0nXiO5v3HjyU@IwubK$]">
                                                <field name="TEXT"></field>
                                              </shadow>
                                              <block type="variables_get" id="Q?gQOdIb]o-ZGGec5m{G">
                                                <field name="VAR" id=":Fbza.{0*q*jalJ+tc#.">Expected Profit</field>
                                              </block>
                                            </value>
                                            <next>
                                              <block type="text_statement" id="Nh7Hvn=(XtH,v#*Cjb/x">
                                                <value name="TEXT">
                                                  <shadow type="text" id="4o?;Dxd3i6+IBAb-|fKL">
                                                    <field name="TEXT"></field>
                                                  </shadow>
                                                  <block type="text" id="!u@c_.Ts43Ade~%zt8$U">
                                                    <field name="TEXT">  |  Stop Loss $</field>
                                                  </block>
                                                </value>
                                                <next>
                                                  <block type="text_statement" id="mC+7r%1#~ypnI5cvNpq5">
                                                    <value name="TEXT">
                                                      <shadow type="text" id=":B2DUUnPJ/3yvwUljJFn">
                                                        <field name="TEXT"></field>
                                                      </shadow>
                                                      <block type="variables_get" id="W.m=aiTsNnf;^6~8#bNB">
                                                        <field name="VAR" id="BTQ{$u318X:bRnhP(mQ9">Stop Loss</field>
                                                      </block>
                                                    </value>
                                                  </block>
                                                </next>
                                              </block>
                                            </next>
                                          </block>
                                        </next>
                                      </block>
                                    </statement>
                                    <next>
                                      <block type="notify" id="G@~{)p?Yb7{%`oo+cePB" collapsed="true">
                                        <field name="NOTIFICATION_TYPE">info</field>
                                        <field name="NOTIFICATION_SOUND">earned-money</field>
                                        <value name="MESSAGE">
                                          <shadow type="text" id="x,A7;~@E*2^CC+FqEE0E">
                                            <field name="TEXT">abc</field>
                                          </shadow>
                                          <block type="variables_get" id="Et_%#)~ho|XR%T{S8B#`">
                                            <field name="VAR" id="2%u_7^a8rtYPr1vwtnOB">text</field>
                                          </block>
                                        </value>
                                        <next>
                                          <block type="variables_set" id="HDRN{#A`/wArxe});Xx]">
                                            <field name="VAR" id="`=|V?TV%1c6]^Pvh=CK/">Loss</field>
                                            <value name="VALUE">
                                              <block type="math_number" id="e?u~(LU?;S7?wi4`40jV">
                                                <field name="NUM">0</field>
                                              </block>
                                            </value>
                                          </block>
                                        </next>
                                      </block>
                                    </next>
                                  </block>
                                </next>
                              </block>
                            </next>
                          </block>
                        </next>
                      </block>
                    </next>
                  </block>
                </next>
              </block>
            </next>
          </block>
        </next>
      </block>
    </statement>
    <statement name="SUBMARKET">
      <block type="trade_definition_tradeoptions" id="Q%0.[CGm6dl?f44`VG1;">
        <mutation xmlns="http://www.w3.org/1999/xhtml" has_first_barrier="false" has_second_barrier="false" has_prediction="false"></mutation>
        <field name="DURATIONTYPE_LIST">t</field>
        <value name="DURATION">
          <shadow type="math_number" id="=7?(L5oI~FHx8*lK}2|7">
            <field name="NUM">1</field>
          </shadow>
          <block type="math_number" id="5OMtGE?tQ)KjCt%4qr70">
            <field name="NUM">1</field>
          </block>
        </value>
        <value name="AMOUNT">
          <shadow type="math_number" id=")solnHAXTV@+ZzO2:?iQ">
            <field name="NUM">0.1</field>
          </shadow>
          <block type="variables_get" id="/DA#bhl2dc*Hag8@Q8NQ">
            <field name="VAR" id="9dQ4tsj$@`vWpu;:2{K=">Stake</field>
          </block>
        </value>
      </block>
    </statement>
  </block>
  <block type="after_purchase" id="/oDFJ|IGtwp;kNfx;1RD" x="836" y="110">
    <statement name="AFTERPURCHASE_STACK">
      <block type="controls_if" id=")L?q6^NxtS?@2w3ws85L">
        <mutation xmlns="http://www.w3.org/1999/xhtml" elseif="1"></mutation>
        <value name="IF0">
          <block type="contract_check_result" id=")4cRE8g%fnWLy.#a.wc1">
            <field name="CHECK_RESULT">win</field>
          </block>
        </value>
        <statement name="DO0">
          <block type="variables_set" id="h;?+}kW+]V?eyX`c0F{W">
            <field name="VAR" id="9dQ4tsj$@`vWpu;:2{K=">Stake</field>
            <value name="VALUE">
              <block type="variables_get" id="bh:[.Ncb^HqKccNq9s=?">
                <field name="VAR" id="!P]:?:q)?v?}qINF%J42">Win Stake</field>
              </block>
            </value>
            <next>
              <block type="variables_set" id="oEGFpZL2cO1fw%[^zp|k">
                <field name="VAR" id="`=|V?TV%1c6]^Pvh=CK/">Loss</field>
                <value name="VALUE">
                  <block type="math_number" id="OA728K^7em3Xt_=96vXH">
                    <field name="NUM">0</field>
                  </block>
                </value>
              </block>
            </next>
          </block>
        </statement>
        <value name="IF1">
          <block type="contract_check_result" id="V*`uiaxlr~|52Ge]8JEP">
            <field name="CHECK_RESULT">loss</field>
          </block>
        </value>
        <statement name="DO1">
          <block type="variables_set" id="4?18[1),2cG25rran%=|">
            <field name="VAR" id="`=|V?TV%1c6]^Pvh=CK/">Loss</field>
            <value name="VALUE">
              <block type="math_arithmetic" id="/P{dDY?BC%9I0[QIF6!.">
                <field name="OP">ADD</field>
                <value name="A">
                  <shadow type="math_number" id="m3!^-s/P^x.tOOfuQv~~">
                    <field name="NUM">1</field>
                  </shadow>
                  <block type="variables_get" id="9hNpNb~Nv#4GK{em)X%M">
                    <field name="VAR" id="`=|V?TV%1c6]^Pvh=CK/">Loss</field>
                  </block>
                </value>
                <value name="B">
                  <shadow type="math_number" id="40Z8Ig*{:.6S`:[zj)@~">
                    <field name="NUM">1</field>
                  </shadow>
                </value>
              </block>
            </value>
            <next>
              <block type="controls_if" id="l+t2iurggEgne[ObY|*J">
                <value name="IF0">
                  <block type="logic_compare" id="GvS=^Bir_e8.k?,v)jXy">
                    <field name="OP">GTE</field>
                    <value name="A">
                      <block type="variables_get" id="_mTKDUI}9|bc)kQWyl-q">
                        <field name="VAR" id="`=|V?TV%1c6]^Pvh=CK/">Loss</field>
                      </block>
                    </value>
                    <value name="B">
                      <block type="math_number" id="jVw}LH%/,0~xTe.gywy{">
                        <field name="NUM">1</field>
                      </block>
                    </value>
                  </block>
                </value>
                <statement name="DO0">
                  <block type="variables_set" id=")M`@soq|s*EZbh$ia66V">
                    <field name="VAR" id="9dQ4tsj$@`vWpu;:2{K=">Stake</field>
                    <value name="VALUE">
                      <block type="math_arithmetic" id="Ps0@`t2$w3IbH5QJV,po">
                        <field name="OP">MULTIPLY</field>
                        <value name="A">
                          <shadow type="math_number" id="m=@`4%x%?Pxoz!adbbt/">
                            <field name="NUM">1</field>
                          </shadow>
                          <block type="math_single" id="*GY!p|CoPEeZukAY~v*H">
                            <field name="OP">ABS</field>
                            <value name="NUM">
                              <shadow type="math_number" id="VTeU-1Wp{d0,VD2.j`?,">
                                <field name="NUM">9</field>
                              </shadow>
                              <block type="read_details" id="q*!.IN2YPTNS,xQmP8,d">
                                <field name="DETAIL_INDEX">4</field>
                              </block>
                            </value>
                          </block>
                        </value>
                        <value name="B">
                          <shadow type="math_number" id="PMP%$%cEa_O)T/aqNw0y">
                            <field name="NUM">2.1</field>
                          </shadow>
                        </value>
                      </block>
                    </value>
                  </block>
                </statement>
              </block>
            </next>
          </block>
        </statement>
        <next>
          <block type="controls_if" id="7}AJx2e*._.@b?G:CeB|">
            <mutation xmlns="http://www.w3.org/1999/xhtml" elseif="1"></mutation>
            <value name="IF0">
              <block type="contract_check_result" id="[%!M)m%xNaGN%?#=`WK/">
                <field name="CHECK_RESULT">loss</field>
              </block>
            </value>
            <statement name="DO0">
              <block type="controls_if" id="|n0DTqhBDzeJQPe8]@c+">
                <mutation xmlns="http://www.w3.org/1999/xhtml" else="1"></mutation>
                <value name="IF0">
                  <block type="logic_operation" id="QPJM+M2NK:~EK^*)65e]">
                    <field name="OP">AND</field>
                    <value name="A">
                      <block type="math_number_property" id="kU41%b2=ogL.:0.3EE:K">
                        <mutation xmlns="http://www.w3.org/1999/xhtml" divisor_input="false"></mutation>
                        <field name="PROPERTY">NEGATIVE</field>
                        <value name="NUMBER_TO_CHECK">
                          <shadow type="math_number" id="mW9r)4LgpGD{rZ:JfA}~">
                            <field name="NUM">0</field>
                          </shadow>
                          <block type="total_profit" id="7G.mcX|9MeMv#J6;/)Aw"></block>
                        </value>
                      </block>
                    </value>
                    <value name="B">
                      <block type="logic_compare" id="Nje`8#GI4o|rjGls8Rxj">
                        <field name="OP">GTE</field>
                        <value name="A">
                          <block type="math_single" id="aum_=gYvJhS)rD:du[w-">
                            <field name="OP">ABS</field>
                            <value name="NUM">
                              <shadow type="math_number" id="m)sE7beehxu9[dt-E~33">
                                <field name="NUM">9</field>
                              </shadow>
                              <block type="total_profit" id="o|4URiooafb(|Dc:WuRn"></block>
                            </value>
                          </block>
                        </value>
                        <value name="B">
                          <block type="variables_get" id="9H
