<template>
  <div class="w-100">
    <div class="mobileTitle">
      Вопросы - ответы
    </div>
    <div class="boxContainer">
      <div class="componentPath">
        <div>Ценообразование в строительстве » Вопросы-ответы » <span class="currentName">Смета на СМР при упрощёнке (УСН)</span></div>
        <div class="goBack hideOnMobile"><img src="@/assets/icons/triangleLeftIcon.svg" class="m-r-5"> Назад</div>
      </div>
      <AddThemeBtn class="hideOnMobile onlySmallDisplays"/>
    </div>
    <div class="boxContainer m-t-50 row space-btw">
        <span class="viewHeader">Смета на СМР при упрощёнке (УСН)</span>
        <SearchBox class="hideOnMobile"/>
    </div>
    <div class="border-bottom-bold m-t-22 m-b-30"></div>
    <div class="row">
        <div class="person-container">
            <div class="view-person-img m-b-30">
                <div class="active"></div>
                <div class="view-arrow-icons-container">
                    <div class="icon-container"><img src="@/assets/icons/arrowLeftIcon.svg" class="icon"></div>
                    <div class="icon-container"><img src="@/assets/icons/arrowLeftIcon.svg" class="icon"></div>
                </div>
            </div>
            <span class="view-user-name m-b-18">Евгений Ануев</span>
            <div class="progress__bar"></div>
            <div class="progress__bar__percent"></div>
            <div class="progress__bar m-t-8"></div>
            <div class="progress__bar__percent"></div>
        </div>
        <div class="view-main-content">
            <div class="view-post-header m-b-30">
                <div class="post-left-section">
                    <img src="@/assets/icons/clockIcon.svg" width="11px">
                    <span class="view-post-date">6 янв 2020, 15:42:22</span>
                </div>
                <div class="post-right-section"><img src="@/assets/icons/moreIcon.svg"></div>
            </div>
            <img src="@/assets/img/view.jpg" class="post-img m-b-30">
            <div class="view-post-text">
                <strong>ПРИКРЕПЛЕНО:</strong><br><br>
                <span class="activeStyle">Письмо № НЗ-6292 от 10 06.10.2003</span><span>, в приложении к этому письму есть пример расчета, но он носит справочный характер (</span>
                <span class="activeStyle">ПИСЬМО от 16 января 2012 г. N 1076-08/ДШ-05 Минрегиона РФ </span>
                <span>) , т.к. основан на старой структуре НР из отмененного МДС 81-4.99.
                Возмещение входящего НДС при упрощенке рассчитывается по формуле:
                НДС=(МАТ+(ЭМ-ЗПМ)+НР*0,1932+СП*0,15)*0,18 (тут 0,1932 это 0,1712 плюс часть удельного веса затрат, на которые начисляется НДС по прил.8 МДС 81–33.2004, см Консультации и разъяснения, №3(39) за 2005 г.) Если у кого есть желание, может вывести эту формулу для районов КС и приравненным к ним и выложить в этой теме.
                Накладные расходы принимаются с коэффициентом 0,94 (0,7 не накручивается) - Письмо Госстроя от 27.11.2012 № 2536-ИП/12/ГС Сметная прибыль принимается с коэффициентом 0,9 - Письмо Росстроя от 18 ноября 2004 
                года № АП-5536/06 Остальные коэффициенты к НР и СП также как и для неупрощенцев. В связи с отменой письма 2536-ИП/12/ГС отменяется коэффициент 0,94 к НР и взамен снова вступает в силу коэффициент 0,7 к НР, регламентированный действующим МДС-33</span>
            </div>
            <div class="message-footer">
                <span>
                    <span>Цитировать</span>  <img src="@/assets/icons/quoteIcon.svg">
                </span>
            </div>
        </div>
    </div>
    <div class="forum-messages m-t-50">
      <hr class="messages-hr">
      <div class="forum-message">
        <div style="min-width: 140px"></div>
        <div class="left-section">
          <div class="time-section">
                <span>
                    <img src="@/assets/icons/clockIcon.svg"> 6 янв 2020, 15:42:22
                </span>
            <img src="@/assets/icons/complainIcon.svg">
          </div>

          <div class="message-text">
            НР*0,183 это по отмененному МДС 81-4.99, в соответствии с Приложением 8 к МДС 81–33.2004 удельный вес
            материалов в постатейной структуре накладных расходов равен 17,12 %, т.е. НР*0,1712 и еще добавляется часть
            удельного веса прочих затрат, на которые начисляется НДС, 0,0551*0,4=0,022 (Расходы на оплату
            консультационных, информационных, юридических и др. услуг, оплата банковских услуг, расходы на рекламу,
            расходы по нормативным работам, по проектированию производства работ, выполняемому сторонними организациями
            и т.д., что составляет около 40% от прочих затрат - 5,51% в накладных расходах.)
            Это хорошо расписано в Журнале "Консультации и разъяснения ... " выпуск 3, 2008г.
            итого НР*0,1932
          </div>
          <div class="message-footer">
                <span>
                  <span>Цитировать</span>  <img src="@/assets/icons/quoteIcon.svg">
                </span>
            <span>
                   <img src="@/assets/icons/shareIcon.svg">
                </span>
          </div>
        </div>
      </div>
      <div class="forum-message colored">
        <div style="min-width: 140px"></div>
        <div class="left-section">
          <div class="time-section">
                <span>
                    <img src="@/assets/icons/clockIcon.svg"> 6 янв 2020, 15:42:22
                </span>
            <img src="@/assets/icons/complainIcon.svg">
          </div>

          <div class="message-text">
            А это,если несложно, поясните...на каком основании ..
            <br>
            <br>
            У вас берутся в аренду механизмы без механизаторов??? сами рулить будете?
            Вопрос не риторический. Если по Письмо № НЗ-6292/10 06.10.2003, то правильно якобы, а в жизни? по логике
          </div>
          <div class="message-footer">
                <span>
                  <span>Цитировать</span>  <img src="@/assets/icons/quoteIcon.svg">
                </span>
            <span>
                   <img src="@/assets/icons/shareIcon.svg">
                </span>
          </div>
        </div>
      </div>
      <div class="forum-message reply">
        <div style="min-width: 140px"></div>
        <div class="left-section">
          <div class="time-section">
                <span>
                    <img src="@/assets/icons/clockIcon.svg"> 6 янв 2020, 15:42:22
                </span>
            <img src="@/assets/icons/complainIcon.svg">
          </div>

          <div class="replied-message">
            <div class="reply-title">
              Цитата: <span class="username">Елена Кузнецова</span>
            </div>
            <div class="reply-text">
              А это,если несложно, поясните...на каком основании ..
              <br>
              <br>
              У вас берутся в аренду механизмы без механизаторов??? сами рулить будете?
              Вопрос не риторический. Если по Письмо № НЗ-6292/10 06.10.2003, то правильно якобы, а в жизни? по логике
            </div>
          </div>
          <div class="message-text">
            Елена Кузнецова, спасибо. Да твердой она в данном случае быть не может.
          </div>
          <div class="message-footer">
                <span>
                  <span>Цитировать</span>  <img src="@/assets/icons/quoteIcon.svg">
                </span>
            <span>
                   <img src="@/assets/icons/shareIcon.svg">
                </span>
          </div>
        </div>
      </div>
      <hr class="messages-hr">
    </div>
    <table class="forumTableContainer m-b-75">
      <tr>
        <th>Вопросы - ответы</th>
        <th>
          <img src="@/assets/icons/repliesIcon.svg">
          <span>Ответы</span>
        </th>
        <th>
          <img src="@/assets/icons/viewsIcon.svg">
          <span>Просмотры</span>
        </th>
        <th>
          <img src="@/assets/icons/autorIcon.svg">
          <span>Автор</span>
        </th>
        <th></th>
      </tr>
      <tr>
        <td>
          <div>
            <div class="first-row">
              <span class="title">Смета на СМР при упрощёнке (УСН)</span>
              <span class="pageNumbers">[1,2,3...107,108,109]</span>
            </div>
            <div class="lastVisit">
              <span>Учет НДС в сметах при упрощенной системе налогообложения</span>
            </div>
          </div>
        </td>
        <td>34</td>
        <td>234</td>
        <td><span class="autor">Елена</span></td>
      </tr>
      <tr>
        <td>
          <div>
            <div class="first-row">
              <span class="title">Установка и разборка инвентарных лесов</span>
              <span class="pageNumbers">[1,2,3...107,108,109]</span>
            </div>
            <div class="lastVisit">
              <span>Учет НДС в сметах при упрощенной системе налогообложения</span>
            </div>
          </div>
        </td>
        <td>34</td>
        <td>234</td>
        <td><span class="autor">Автор</span></td>
      </tr>
      <tr class="specialRow">
        <td>
          <div>
            <div class="first-row">
              <span class="title"> Установка и разборка инвентарных лесов</span>
              <span class="pageNumbers">[1,2,3...107,108,109]</span>
            </div>
          </div>
        </td>
        <td>34</td>
        <td>234</td>
        <td>
          <span class="autor">Автор</span>
        </td>
        <td>
          <img src="@/assets/icons/drugIcon.svg" class="m-r-5">
        </td>
      </tr>
      <tr>
        <td>
          <div>
            <div class="first-row">
              <span class="title">Сборники ЕНиР</span>
              <span class="pageNumbers">[1,2,3...107,108,109]</span>
            </div>
            <div class="lastVisit">
              <span>Вопросы по ЕНиР задаем здесь</span>
            </div>
          </div>
        </td>
        <td>34</td>
        <td>234</td>
        <td><span class="autor">Автор</span></td>
      </tr>
      <tr>
        <td>
          <div>
            <div class="first-row">
              <span class="title">Твердая договорная цена</span>
              <span class="pageNumbers">[1,2,3...107,108,109]</span>
            </div>
            <div class="lastVisit">
              <span>Вопросы про твердую договорную цену задаем здесь</span>
            </div>
          </div>
        </td>
        <td>34</td>
        <td>234</td>
        <td><span class="autor">Автор</span></td>
        <td>
          <img src="@/assets/icons/drugIcon.svg" class="m-r-5">
        </td>
      </tr>
      <tr>
        <td>
          <div>
            <div class="first-row">
              <span class="title">Сборники ЕНиР</span>
              <span class="pageNumbers">[1,2,3...107,108,109]</span>
            </div>
            <div class="lastVisit">
              <span>Вопросы по ЕНиР задаем здесь</span>
            </div>
          </div>
        </td>
        <td>34</td>
        <td>234</td>
        <td><span class="autor">Автор</span></td>
      </tr>
      <tr>
        <td>
          <div>
            <div class="first-row">
              <span class="title">Установка и разборка инвентарных лесов</span>
              <span class="pageNumbers">[1,2,3...107,108,109]</span>
            </div>
            <div class="lastVisit">
              <span>Учет НДС в сметах при упрощенной системе налогообложения</span>
            </div>
          </div>
        </td>
        <td>34</td>
        <td>234</td>
        <td><span class="autor">Автор</span></td>
      </tr>
    </table>
    <Pagination />
  </div>
</template>

