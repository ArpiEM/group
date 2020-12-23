<template>
  <div class="form configurations">
    <div class="container">
      <div class="container-settings">
        <ConfigurationBtns />
        <div class="container-settings-right">
          <button class="back-btn pointer">
            <img
              src="@/assets/icons/triangleLeftIcon.svg"
              class="m-l-30 m-r-5"
            />
            Назад
          </button>
          <button class="save-btn pointer">Сохранить</button>
        </div>
      </div>
      <h1 class="container-title">Категории</h1>
      <table class="forumTableContainer m-b-75">
        <tr>
          <th>Вопросы - ответы</th>
          <th>
            <img src="@/assets/icons/repliesIcon.svg" />
            <span>Ответы</span>
          </th>
          <th>
            <img src="@/assets/icons/viewsIcon.svg" />
            <span>Просмотры</span>
          </th>
          <th>
            <img src="@/assets/icons/autorIcon.svg" />
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
                <span
                  >Учет НДС в сметах при упрощенной системе
                  налогообложения</span
                >
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
                <span class="title"
                  >Установка и разборка инвентарных лесов</span
                >
                <span class="pageNumbers">[1,2,3...107,108,109]</span>
              </div>
              <div class="lastVisit">
                <span
                  >Учет НДС в сметах при упрощенной системе
                  налогообложения</span
                >
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
                <span class="title">
                  Установка и разборка инвентарных лесов</span
                >
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
            <img src="@/assets/icons/drugIcon.svg" class="m-r-5" />
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
            <img src="@/assets/icons/drugIcon.svg" class="m-r-5" />
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
                <span class="title"
                  >Установка и разборка инвентарных лесов</span
                >
                <span class="pageNumbers">[1,2,3...107,108,109]</span>
              </div>
              <div class="lastVisit">
                <span
                  >Учет НДС в сметах при упрощенной системе
                  налогообложения</span
                >
              </div>
            </div>
          </td>
          <td>34</td>
          <td>234</td>
          <td><span class="autor">Автор</span></td>
        </tr>
      </table>
    </div>
    <button class="container-btn">+ Добавить категорию</button>
  </div>
</template>