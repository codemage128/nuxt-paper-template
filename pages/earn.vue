<template>
  <div class="main">
    <div class="section section-buttons">
      <div class="container mt-5">
        <Dashboard />
        <div class="row">
          <div class="col-md-12 mt-3">
            <h5>OFFERWALLS</h5>
            <span class="comment">
              Click Open Offerwall and start completing free offers to earn
              Robux!
            </span>
          </div>
        </div>
        <div class="row mt-5">
          <div class="col-md-4 com-xs-6">
            <div class="card">
              <div class="card-body card-overwall-first">
                <img
                  src="https://rbxcloud.com/img/adgate.55cef36e.png"
                  height="102px"
                />
              </div>
            </div>
          </div>
          <div class="col-md-4 com-xs-6">
            <div class="card">
              <div class="card-body card-overwall-second">
                <img
                  src="https://rbxcloud.com/img/adgem.ed4d12c1.png"
                  height="102px"
                />
              </div>
            </div>
          </div>
          <div class="col-md-4 com-xs-6">
            <div class="card">
              <div class="card-body card-overwall-third">
                <img
                  src="https://rbxcloud.com/img/ogads.73db3312.png"
                  height="102px"
                />
              </div>
            </div>
          </div>
          <div class="col-md-4 com-xs-6">
            <div class="card">
              <div class="card-body card-overwall-fourth">
                <img
                  src="https://rbxcloud.com/img/adscend.49d21957.png"
                  height="102px"
                />
              </div>
            </div>
          </div>
          <div class="col-md-4 com-xs-6">
            <div class="card">
              <div class="card-body card-overwall-fifth">
                <img
                  src="https://rbxcloud.com/img/offertoro.979aaa54.png"
                  height="102px"
                />
              </div>
            </div>
          </div>
          <div class="col-md-4 com-xs-6">
            <div class="card">
              <div class="card-body card-overwall-sixth">
                <img
                  src="https://rbxcloud.com/img/ayetstudios.d6b52bb9.png"
                  height="102px"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12 mt-3">
            <h5>FOLLOW US</h5>
            <span class="comment"> Join Us and Earn free Robux </span>
          </div>
        </div>
        <div class="row mt-5">
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <div class="row">
                  <div class="col-md-12 text-center">
                    <img
                      src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFUAAABVCAYAAAA49ahaAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAoWSURBVHgB7Z1/bJR3HcffvR70h7QrWLKVuXEL2SyJ0hYXInEr1+hfTqTIHxrlR41EyaKB/eHMNg0lRIzyByWbYVlQWhaWoAkbKuoIjpZlmqhx1yWGFhQedIXqGlZ6pVxp77rP+7nnud0999z1fjy/7rpX8s3z6zju3v18v5/P9/P9cRXwAIFAoKG6urq1oqKiJRaLBXiLRa4btHMjytzc3Lg8H5djyOfz8XowEomEFEUZh8tUwAV0EUWITXIZFHFaYREUWQ798p6nh4aG+uECjora3NwclMMO+cKd8uUbYDOaJb8mp31OCmy7qJpV7pEvuNsJIbOgSOmWMiACK7AR20T1kJhGFCl9UnrtEtcWUaWad3tQTCMK4s1CNyzGUlG1NvMYzD22V1GkfNPKNtcSUVnVa2pqusUyd6NEkZrVc+fOnX1WhGRFiyrWGZDDeZSWdWZCkdJRbFvrQxGIoF3yF34b5SEoCUhte1u+1w4UQSUKhM5IDoekVKOMECPh9+lsbGysGBsb60cBFCSqJuhelDfBQoXNW9QFIqhOQcLmJeoCE1Qnb2FzFnWBCqqTl7A5iUovj7hTWshQWEWEHZzvhfPGqYxDGTZ5vMvpCFoOt22+ODZrnMqekhzOfyRoHC1pfl7TJSNZRWXXE+UT2FtFQHTJ6lsyVn8tOXIeHmD2/hUY7ftFxueNz/4I1X/9OxymI1MSxp/lHx2Dh6CwGZ+tWAEXoD4PmT0wFVULnwLwIC/JR15pvPmJzyD6n7/gzD1TUm7DIQKi016x1n3GB2ltqpZ1KiqhYCft0mK1y8dOLo890Y61U1VqcRJx4HvMnJaZo+pCiTknX+A++INr0DRTcH6oIBgNyJBRWg45RVSvW2k2qvZux8PTi1AXc3bU3cxajZYaRImGUP5gC5ZtfAzt4Ro4iZm1GkUt6b59zbHvY+PSVXAaWmvydUJULS4NoISpaFiCx888j6/f46ywtFZNP5VkSy3JttSIL3Avdp99BR/fvAkOk9AvISqn4qBMqK+vx4kDP0HluT9icvOX4QTSBHTqDkt1lV7qkprB3tS75/6gng9hkQT/uXn4a5jDjxHFifAtLL44JGUY/uvXUX/8BGxC7bqqlipW6nhdcQKKzx7Yi3VL8ci6dZjYsRUT27fCLrRZjIluahBlzDZp5VjeEct9M7oIV2/V4saiKP5ROw0r8fl8QR79ra2tDZFIxLL5oV5mjVjup2KVCN9Ypl5/tvldWIlYaivbVV85CBrpPo6YMgovwMnMPk4JR4kTU/6H8EPbRNyXXRdXrLWFbWoALhGrq8Pd1Z9UvbueE/WFw1jy6m/UY76c6jmCR1/5PR743FrJBWxTEy0uEPCzHYCDUMipL3RgsnMTIuseNX0NQ5/qv+Wfyafz2Sru6Ku/u4KdvWdR2boKlRta1AwWe1sUmVZtMwE/u1giLJxg6vMduPnM06ZZ/AZxIg8i7kxqJ2swJrlRinRj0SzyIVwZw9HGCTVZvfPqbaz95zCaDp+CU0gEoFqq7SOltM6bzz4t1pnau6GQ35VQZ6uU5IB+8madZPKXq+KwFAL/IPub3lfPmbzeMFmNhyOLpTA9WNRkx6xQT9vbVFrl/5/vUdtOHQr4HCrV2NEJGI8aY9KmGT9sImDbO+sYBaWQPxNBG9xZwpUg32YlH2w1FbafyYL+UMRkt9FtQe3GNlEp5sT2bySuKehzWaZu0Ss74JkdwbbqP3Zgf+KcI55mgjJQn+55FTN9r2NuPD60HPbNSepuCUoZiqrAYmfF+PNu84fV/iUTQad7TmF63/GEmDocuDPeKzEUv7Z+E1bCwF5nmyFcInd7X0fkqSMp9xhXcjKEHpsy/JmsjKLUoJ7+WCymWLmKmSQ7J2O1V6v8vpcT1xSQ8aQx5LlcfRf5YmOYlDOcbunX1srDKmL1dYmq325ipbP9gwmHREGffPA91TrLBXX/AcTbVMtIniy20SR0mnntz4lz9pbKSVANxccdHWAhtFSdNSYR29z4pHqklbINLTekKQ35JKkagoX4R64nzleaPGe2iFyqnkGuMHeQDf0P5QUk6T/oC4VCnMdumbDJeVCzUU+m48jlqtxFTXZ8ZnhFVOrIBcN6/eyHRfgmwglhx5HuAKv2fEW11nwmkiWHaGbEBq/AC0gk1c+jKqq0q6dhIbXn3lCPt0yeUVBm5RmH5gInQ+jJbFq+0fqjoX+ltNNuIpbK/VriorJdZdAKi6j9U3xexjsZntNa13/7a/NaK8VkUkan3aQ5YTdX51JV/rGtVTA+HRoaGuC5KirbVW1XHEugqGwCLiBzuFR96El858AB01EANaktYnLxhO6k9ByskejAh8HL5Tycn9XoVkqSuyDcrKULFtHwwhH89pkf4GCW13xrSydubPkSDl68qEYNvvCEdBya0xwTU4W/Uuf6p1oq8wd6R4JW6nLM26ufpHzK1atXv2/l8Aot7fS69abVNhkZWFbnPF0zcWzslTEhYxSU3d3Jtl2J5Mv+pptuxr2KVP3ESpWUT8rVFojv3WQJrNqP9P0SZ+5fmdPrL4i4FzRhG9QFExXqQKAROiYKmtzd3bzK1fH+LhG1T79I6fKIwzpspcNilR763m68OPLfnF5Pq2Qym4UDgmsyWPidPUdSEtqFDg5ahCJlIPlGiqiaw+qBhXAM/+iOLoyMjKBYdAud6TubuBcfjna1u5u2aVha59xqayW3xWK3b9oC5ee/RqEwu0VBo6F/J+4xB+sBK+0z3kyLUUZHRyONjY3cnCUICwnPTOONty5g/Qtvoo6zVFbdi6qq+ReTUcyproNqDjZ5RODksjB+ep/ru3r2iJWmdZyyLfi9ChvmBNRFfdg5Vo8v3voY/MFPo+HxNhF4OeofiMer9Oqs5tHQFcyefittaCXsi+Ho8gmcXOp6fz/F4yfj2ipqrs6juE+IuLlAMU8um1QtlIODHiCo96CMZA0gJW49ZFwjZDUUV19XyuGQ5KWQl6pmMbp4BgNLIurwikfEZJe0Z3h4+KlMz7OKqs2yLqcd0qxAEU3asu0JmHUyBUMsOXRYHQ2UKpoOHfNtsjjvsuOxsbFxiQYYaZfNOqsi2JWpHU0mp7XcImxIhOVpEAuXbhH0cC4vzHmBvAg7sICF7TbbgSITee06sECFzUtQkvdWDgtM2LwFJQXtj7FAhC1IUFLwpiOasNckzAiijDam1cKmXbk6JdP3QJF8tCd1OkXPpOYHkHRhG3cfRwnDrid7Slb8oIKlk+9LeJ//rlyC+lyxZUWDNtbVBQ+Lq0127inUGWV9b9hE0h5XXfCQuLqYUtUP2/XbVbavvdHEDSK+PVMALuGEmIn/Cw4iAm+QQ5cLv0fVa2WbOe//C5egwNwhh1tkWLmSm9MZOfuO03A4V9SNn6fzxNI77berWrigg7/xx6O2ujvjb/xpQbrChSDauoWQWyIa+QBPsVJ2YrlrxgAAAABJRU5ErkJggg=="
                    />
                    <h3>TikTok</h3>
                    <span
                      >Follow our TikTok account for free robux promotion
                      codes</span
                    ><br />
                    <button class="btn btn-lg btn-success btn-round mt-2">
                      +0.5 ROBUX
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <div class="row">
                  <div class="col-md-12 text-center">
                    <img
                      src="https://rbxcloud.com/img/instagram_rounded.aca50a42.png"
                    />
                    <h3>Instagram</h3>
                    <span
                      >Follow our Instagram account for free robux promotion
                      codes</span
                    ><br />
                    <button class="btn btn-lg btn-success btn-round mt-2">
                      +0.5 ROBUX
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <div class="row">
                  <div class="col-md-12 text-center">
                    <img
                      src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFUAAABVCAYAAAA49ahaAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAUySURBVHgB7Z3tedowEMfPefq9dII6E4RMgDtB2QAyQdIJTCcoG5BskE4AmQAygd0JoBNcdZadOFQ26LD1Yvv3PIcJOID/nE7S6YUAHAABRuIwFnYjLCzZKD8ekwo75LbL/36l+4F8zCoBWKAk4ndhUX6/KUjkjbDfgTx2GyFmJGwlbC8MDdg+f78IugR5pbCFQSGrLBE2Q3U48QOHxFSJu/BOXEfFVIoLroMyZiaOi6kSNwLXQFnUl56IWGW/ULZK7CM+SIj+eWed14ZgE/EB5uh+7NQ1up4Z2ABlZeSTWLq2AJP0QFCzwvZIUDPC9lDQdoXtsaDtCIuylvdJgLZsdo5eJ1N/KNttW3ClYWwXytXeBjJ/W0mtqCiFJEFDGChIQQpbmQy/gnoWMAh6TCgsrjuh0lNRJhnWMFDFt6qRhTpRExi8tI5UiHetekJZ/HEo9udAiSRlGPjPU/Panop9CI28dfh+HI2kEZ8/v98vn3cJafrx7z9/Pj5+OEg7Po8PVVbXx5XWJ8WJc+AKGkXSbsRI83jcjFBtQcKS7cTg68sLwPMzMCCvuBf2s/IM5OZGRyPE5RK9JkkQo4jTIdhjXRue1XMiQbdb7AyzGUfYuE7URPsFVyvsFPs9Yhhqe2uVoJG2oPTmXWS95nhrVGhZblLNQJf7e+gkVNmOtFMdb/qVRZ2CLuMmp0A5hv61TYsKKxM1d139LBR9o12FmoV6FJPu3jz1O+jichu0CXilMNOxEDUCXbouKu/6Irq5wpLbaqEfyP2CJ+qY9CRP5dU2X79CK2w2AI+PYB2+04xJVO2IfOGb1kP98bs7ac0lPvThX98NiRoCh7aLP3nrtUhX/vhhT1zeNYb84m8qpi6XIsf+zU5IoPSkPpmo7tc4RUggz6WY6zYXiGqjSUXikteairdfvgCDET+m2qSIt4uFzOS3xQXF319+ioT77a0bTbASfotKlONtm16rgf+iEtRPX62c6eX5LSqJSE2u7dapjBmJmgIH20Xt4UEM/iTtJsp5LYyUhqh56tgSlTySirq7WbID31NNQyKu19LcTjse3C/+FDepPUpF3XTcLGa46LGj4p8CBxOiUtyMY99yt1lMfQUOvG/xPMgjSUybNTq/G5x56g44tOWpUzGoO5+Ddfiivl4F7/uQmHrTelwp6jynyfZwKRr/G9DFZlbeBLzr29BNIepv0KXZeZ7uwcvbPtNNISoVf31/3/HCsRfoV8QHUfRf6E4mah5X9We9up+F51FMBtbjTb9yQuUJdHl6cibd1iiUpNHnUfkocjZEmE6xU9CMav1plElZx+PUn/5XRHPlaRi5C1CRpzEwfRaVz6DcYIa3fQdNAPZ1VjXNno5jjodmXopH43yqJT8xXLoMezKRjfhihUqx1Ke85MdUpkm13Kd8pMr2si73IjhanaISla6aYoS5rg0JrRq5rBP+719Rpvbqx81VninI5ZTpyTPJW5lFoW8Wq/QLaoRNYFhKWYfe2tScOxioY171RKWo+bJrViu4ByyLLqmKoO4/cdiZQkUKJ3amqBWVwGEPlTJn7aFycjJF/gId6TJdzMNZzadzGZpZ9fumDMK6ImiPhY3BBD0SNgaT9EDYGGyAw06/7YDDntTtgDK5/csj8VTmzu7pZdDfff4n4DooK7HEcTEpdsbgE5hv2+aguPv8c/mby8jFnTsgrv9iqqDYhXZ+j2oCfSAXmGrcbcNCbvPXndjyypP5VBPkF0+bOYgx7aydSMcRnP6Nv7RkNPnpNXDgN/7+Aac5iKUW7KxNAAAAAElFTkSuQmCC"
                    />
                    <h3>Youtube</h3>
                    <span
                      >Subscribe to our Youtube channel to Get free promotion
                      codes!</span
                    ><br />
                    <button class="btn btn-lg btn-success btn-round mt-2">
                      +0.5 ROBUX
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <div class="row">
                  <div class="col-md-12 text-center">
                    <img
                      src="data:image/png;base64,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"
                    />
                    <h3>Discord</h3>
                    <span
                      >Join our Group to learn more about our services and
                      community!</span
                    ><br />
                    <button class="btn btn-lg btn-success btn-round mt-2">JOIN</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <div class="card-body">
                <div class="row">
                  <div class="col-md-12 text-center">
                    <img
                      src="data:image/png;base64,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"
                    />
                    <h3>Twitter</h3>
                    <span
                      >Follow Us On twitter for Daily Free Robux Promocodes And
                      Updates</span
                    ><br />
                    <button class="btn btn-lg btn-success btn-round mt-2">FOLLOW</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <img src="https://rbxcloud.com/img/EasyRBX.80b01b17.png" width="100%" height="90%"/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.card-overwall-first {
  display: flex;
  height: 215px;
  width: 100%;
  background: rgb(47, 128, 237);
  box-shadow: rgba(47, 128, 237, 0.22) 0px 13px 22px;
  border-radius: 4px;
  align-items: center;
}
.card-overwall-second {
  display: flex;
  height: 215px;
  width: 100%;
  background: rgb(115, 89, 165);
  box-shadow: rgba(115, 89, 165, 0.2) 0px 13px 22px;
  border-radius: 4px;
  align-items: center;
}
.card-overwall-third {
  display: flex;
  height: 215px;
  width: 100%;
  background: rgb(26, 182, 255);
  box-shadow: rgba(26, 182, 255, 0.2) 0px 13px 22px;
  border-radius: 4px;
  align-items: center;
}
.card-overwall-fourth {
  display: flex;
  height: 215px;
  width: 100%;
  background: rgb(14, 157, 207);
  box-shadow: rgba(14, 157, 207, 0.22) 0px 13px 22px;
  border-radius: 4px;
  align-items: center;
}
.card-overwall-fifth {
  display: flex;
  height: 215px;
  width: 100%;
  background: rgb(42, 48, 60);
  box-shadow: rgba(42, 48, 60, 0.2) 0px 13px 22px;
  border-radius: 4px;
  align-items: center;
}
.card-overwall-sixth {
  display: flex;
  height: 215px;
  width: 100%;
  background: rgb(242, 148, 0);
  box-shadow: rgba(242, 148, 0, 0.22) 0px 13px 22px;
  border-radius: 4px;
  align-items: center;
}
</style>
