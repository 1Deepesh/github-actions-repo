
# some important points:
## path for github action file : .github/workflows/file-name.yml
### Example Code :
name: First Workflow 
on: workflow_dispatch 
jobs: 
 first-job: 
  runs-on: ubuntu-latest 
  steps: 
   - name: "print greeting."
     run: echo "Hello World!"
   - name: "print Goodbye"
     run: echo "Done - bye!"
