# learning


onFileChanged(event) {
  this.selectedFile = event.target.files[0];
  const fileReader = new FileReader();
  fileReader.readAsText(this.selectedFile, "UTF-8");
  fileReader.onload = () => {
   console.log(JSON.parse(fileReader.result));
  }
  fileReader.onerror = (error) => {
    console.log(error);
  }
}
