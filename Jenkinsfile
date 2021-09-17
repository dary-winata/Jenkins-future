@Library('testing-shared-library') l1
@Library('testing-library') l2
import php;
import phplocal;

node {
    new php(
        node: "dockerworker",
        name: "my-app",
        port: "8181:8080"
    );
    new phplocal(
        node: "vm",
        nama_file: "testing.jar"
    );
}