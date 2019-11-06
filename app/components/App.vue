<template>
  <Page>
    <ActionBar title="My Tasks" />
    <TabView androidTabsPosition="bottom">
      <TabViewItem title="To Do">
        <StackLayout>
          <Label text="This tab will list active tasks and will let users add new tasks." textWrap="true" />
        </StackLayout>
      </TabViewItem>
      <TabViewItem title="Completed">
        <StackLayout>
          <Label text="This tab will list completed tasks for tracking." textWrap="true" />
        </StackLayout>
      </TabViewItem>
    </TabView>

  </Page>
</template>

<script >
export default {
  data() {
    return {
      msg: "Hello World!"
    };
  }
};
</script>

<style scoped>
ActionBar {
  background-color: #53ba82;
  color: #ffffff;
}

</style>
