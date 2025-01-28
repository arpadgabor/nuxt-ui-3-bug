<script setup lang="ts"></script>

<template>
  <div>
    <Form class="w-full flex items-center justify-center h-screen gap-x-4">
      <Field name="field" v-slot="{ componentField }">
        <USelectMenu
          class="w-32"
          placeholder="Select item"
          :items="['Item A', 'Item B']"
          v-bind="componentField"
        />
      </Field>
      <Field name="field_2" v-slot="{ componentField }">
        <USelectMenu
          class="w-32"
          placeholder="Select item"
          :items="['Item A', 'Item B']"
          v-bind="componentField"
        />
      </Field>
      <Field name="field_3" v-slot="{ componentField }">
        <USelect
          class="w-32"
          placeholder="Select item"
          :items="['Item A', 'Item B']"
          v-bind="componentField"
        />
      </Field>
    </Form>
  </div>
</template>
