<template>
  <nb-container>
    <nb-header>
      <nb-left>
        <nb-button transparent :onPress="() => this.props.navigation.goBack()">
          <nb-icon name="arrow-back" />
        </nb-button>
      </nb-left>
      <nb-body>
        <nb-title>Nested Grid</nb-title>
      </nb-body>
      <nb-right />
    </nb-header>
    <nb-grid>
      <nb-col :style="{ backgroundColor: '#DD9E2C' }"></nb-col>
      <nb-col>
        <nb-row :style="{ backgroundColor: '#00CE9F' }"></nb-row>
        <nb-row :style="{ backgroundColor: '#635DB7' }"></nb-row>
      </nb-col>
    </nb-grid>
  </nb-container>
</template>
