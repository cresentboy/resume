<template>
  <div class="content-bd">
    <div class="content-left">
      <section class="practice">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">项目经历</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          <!--经历:-->
          <div class="item">
            <header class="item-hd">
              <h3 class="item-name"></h3>
              <span class="item-time">2019.04 至 2020.03</span>
              <a class="btn item-more" href="#" target="_blank" title=""
                >工作</a
              >
            </header>
            <ol class="item-project">
              <li class="project-1">
                <h3 class="project-name">
                  <a href="#" target="_blank" title="">...</a>
                </h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">...</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          该项目为等多项服务组成。
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>
                            负责项目框架搭建以及疑难问题解决，为项目成员提供开发思路
                          </li>
                          <li>
                            主导整个项目正常开发流程，研究了高可用、高并发服务器的架构设计（keepalived+nginx+haproxy）
                          </li>
                          <li>
                            对常用数据进行缓存处理（Redis），并对[撮合引擎]系统进行了架构设计，采用Redis内存撮合、Rabbit
                            MQ消息队列异步入库实现高性能撮合系统，从而实现撮合引擎弹性伸缩
                          </li>
                          <li>
                            针对Redis可能出现脏读的问题可以采用消息队列处理，消除多线程同一时间操作同一Redis数据的脏读问题；或可以通过Redis锁解决高并发的脏读问题（不推荐，可能会造成无效等待）
                          </li>
                        </ul>
                      </div>
                    </div>
                  </li>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">...</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          该项目前端开发框架采用目前市面流行的Vue.js框架与Element
                          UI 2.0。采用websocket、TradingView、vuex等技术栈
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>
                            负责项目框架搭建以及疑难问题解决，为项目成员提供开发思路
                          </li>
                          <li>
                            主导整个项目正常开发流程，研究K线渲染组件TradingView的使用与原理
                          </li>
                        </ul>
                      </div>
                    </div>
                  </li>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2"></h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          ...
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>
                            ...
                          </li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
              <li class="project-1">
                <h3 class="project-name">
                  <a href="#" target="_blank" title="">...</a>
                </h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">...</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          该项目是
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>负责项目框架搭建</li>
                          <li>
                            介绍
                          </li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
              <li class="project-1">
                <h3 class="project-name">
                  <a
                    href="http://www.ledianyun.com/"
                    target="_blank"
                    title="点击进入->乐店云商城系统"
                    >...</a
                  >
                </h3>
                <ol>
                  <li class="project-2">
                    <div class="item-bd">
                      <h3 class="project-name-2">后台开发</h3>
                      <div class="div-item">
                        <h3 class="project-des">【项目简介】</h3>
                        <p class="item-project-des">
                          <a href="#" target="_blank" title="">乐店云</a
                          >是一个专门为商户提供新零售智慧店铺解决方案的<a
                            href="#"
                            target="_blank"
                            title=""
                            >简介</a
                          >。介绍
                        </p>
                      </div>
                      <div class="div-item">
                        <h3 class="project-des">【工作职责】</h3>
                        <ul class="section-content">
                          <li>
                            负责拼团功能开发，该功能主要涉及用户与用户共同下单逻辑，需要保证在库存无误的情况下，实现多用户订单的提交与交易的正常进行
                          </li>
                          <li>负责官网的开发以及官网搜索引擎优化</li>
                        </ul>
                      </div>
                    </div>
                  </li>
                </ol>
              </li>
            </ol>
          </div>

          <!--经历:伴知旅行-->
          <div class="item">
            <header class="item-hd">
              <h3 class="item-name">河南伴知旅行网络科技有限公司(郑州)</h3>
              <span class="item-time">2020.04 至 2022.03</span>
              <a class="btn item-more" href="#" title="">工作</a>
            </header>
          </div>
        </div>
      </section>
    </div>
    <div class="content-right">
      <section class="skill">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">技能</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          <!--技能:WEB后端开发-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">WEB后端开发</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>
                  两年后端应用Java掌握Java面向对象思想编程
                </li>
                <li>
                  熟练使用Spring Boot、SpringMVC等主流框架，熟悉Restful
                  风格API设计
                </li>

                <li>熟练使用Jwt等用户鉴权产品</li>
                <li>熟悉API开发基本流程，熟悉Restful 风格API设计</li>

                <li>
                  了解Spring cloud，正学习Spring
                  cloud在企业大型应用中的应用，以及大型应用的微服务化及服务治理知识学习
                </li>
              </ul>
            </div>
          </div>

          <!--React-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">数据库</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟悉关系型数据库技术，熟练使用关系型数据库Mysql、Oracle</li>
                <li>
                  熟悉非关系型数据库技术，熟练使用非关系型数据库Nosql：Redis
                </li>
                <li>
                  熟练使用Hibernate JPA，了解 MyBatis、JDBC等数据库操作框架使用
                </li>
                <li>
                  了解分布式数据库及Mycat中间件，并正致力于提高分布式数据库能力和对于数据库高并发高可用的知识储备
                </li>
              </ul>
            </div>
          </div>

          <!-- -->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">服务器|架构</span>
              <a class="btn item-more">熟练掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>..</li>
              </ul>
            </div>
          </div>

          <!-- -->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">开发</span>
              <a class="btn item-more">掌握</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>
                  ....
                </li>
              </ul>
            </div>
          </div>

          <!--Golang-->
          <div class="item">
            <header class="item-hd">
              <span class="item-time">Golang</span>
              <a class="btn item-more">熟悉</a>
            </header>
            <div class="item-bd">
              <ul class="section-content">
                <li>熟悉Golang基本语法与标准库</li>
                <li>用Golang开发过小型项目服务</li>
              </ul>
            </div>
          </div>

         
      </section>

      <!--开源项目-->
      <!-- <section class="project">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">开源项目</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          以下是我的开源项目与学习总结，细节请点击链接查看文档（其他项目开发中，尚未开源，敬请期待）
          <div class="item">
            <header class="item-hd">博客/Github</header>
            <div class="item-bd">
              <ul>
                <li>
                  <a href="http://doc.gangblog.xyz" target="_blank"
                    >笔记仓库</a
                  >
                </li>
                <li>
                  <a href="http://www.github.com/cresentboy" target="_blank"
                    >Github</a
                  >
                </li>
                <li>
                  <a href="http://www.gangblog.xyz" target="_blank"
                    >个人网站主页</a
                  >
                </li>
              </ul>
            </div>
          </div>  
        </div>
      </section> -->
   

      <!--致谢-->
      <section class="thanks">
        <header class="section-hd">
          <span class="section-title-l"></span>
          <h2 class="section-title">致谢</h2>
          <span class="section-title-r"></span>
        </header>
        <div class="section-bd">
          <div class="item">
            <h2 style="font-weight: bold;line-height: 24px;margin-top: 10px">
              感谢您在百忙之中阅读这份履历
            </h2>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
import $ from "jquery";

export default {
  name: "Content",
  components: {},
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  },
  mounted() {
    $(document).ready(function() {
      if ($("ol:first").css("list-style-type") == "none") {
        /* For IE6/7 only. */
        $("ol ol").each(function(i, ol) {
          ol = $(ol);
          var level1 = ol.closest("li").index() + 1;
          ol.children("li").each(function(i, li) {
            li = $(li);
            var level2 = level1 + "." + (li.index() + 1);
            li.prepend("<span>" + level2 + "</span>");
          });
        });
      }
    });
  }
};
</script>
