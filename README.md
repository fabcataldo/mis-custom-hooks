# Notas
Este repositorio contiene varios custom Hooks de React para ayudarme a mi y a quien le sirva, estos hooks.

Tambien la idea es que yo no quiero volver a escribirlos!.

const initialForm = {
  name: '',
  age: 0,
  email: ''
};

const [formValues, handleInputChange, reset] = useForm(initialForm);
