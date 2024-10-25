@Library('JenkinsSandboxLibrary') _
import com.org.foo.*

PipelineConfiguration pl = new PipelineConfiguration()

if (env.BRANCH_NAME == 'main') {
    echo 'Running on main branch'
}

Pipeline(pl)
