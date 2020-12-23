<template>
  <div class="form configurations">
    <div class="container-custom">
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
      <table class="forumTableContainer categories m-b-75">
        <tr>
          <th></th>
          <th>
            <span>Темы</span>
          </th>
          <th>
            <span>Ответы</span>
          </th>
          <th>
            <span>Дата создания</span>
          </th>
          <th></th>
        </tr>
        <tr>
          <td>
            <div>
              <div class="first-row">
                <span class="title">Ценообразование в строительстве</span>
              </div>
            </div>
          </td>
          <td>34</td>
          <td>234</td>
          <td>21.05.2020</td>
        </tr>
        <tr>
          <td>
            <div>
              <div class="first-row">
                <span class="title">Работа ПТО</span>
                <img src="@/assets/icons/penIcon.svg" class="m-l-20" />
                <span class="delete pointer">Удалить</span>
              </div>
              <div class="lastVisit">
              </div>
            </div>
          </td>
          <td>34</td>
          <td>234</td>
          <td>21.05.2020</td>
        </tr>
        <tr class="specialRow">
          <td>
            <div>
              <div class="first-row">
                <span class="title">
                  Установка и разборка инвентарных лесов</span
                >
              </div>
            </div>
          </td>
          <td>34</td>
          <td>234</td>
          <td>21.05.2020</td>
          <td>
            <img src="@/assets/icons/drugIcon.svg" class="m-r-5" />
          </td>
        </tr>
        <tr>
          <td>
            <div>
              <div class="first-row">
                <span class="title">Поиск расценок в ГЭСН, ФЕР, ТЕР и пр.</span>
              </div>
            </div>
          </td>
          <td>34</td>
          <td>234</td>
          <td>21.05.2020</td>
        </tr>
      </table>
    </div>
    <button class="container-btn">+ Добавить категорию</button>
  </div>
</template>
