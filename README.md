# AndroidFileChooser
Usage: 
FileChooser fileChooser=new FileChooser(this).setFileListener(new FileChooser.FileSelectedListener() {
    @Override public void fileSelected(final File file) {
        // do something with the file

    }});
fileChooser.showDialog();
